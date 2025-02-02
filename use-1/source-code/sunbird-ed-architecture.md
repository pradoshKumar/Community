# Sunbird-ED Architecture

## Architecuture

Below architecture diagram explains L0 architectural view of Sunbird-ED

<figure><img src="../../.gitbook/assets/Screenshot 2023-08-04 at 2.25.36 PM.png" alt=""><figcaption></figcaption></figure>

### Learning Apps

These are the client facing applications where users(Admin, Creators & Consumers) can drive some capabilities.

* **Sunbird-Portal UI**\
  The Sunbird portal is the browser-based interface for the Sunbird application stack. It provides a web app through which all functionality of Sunbird can be accessed
* **Sunbird-Mobile-App**\
  The Sunbird Mobile app provides mobility to its feature-rich learning platform. It provides learners with the flexibility to learn anywhere, anytime.
* **Sunbird-Desktop**\
  It is powered by Sunbird-Portal itself. The same code-based being used for offline access of portal application.&#x20;
* **Sunbird-CoKreat (part of Sunbird-CoKreat building block)**\
  [**https://cokreat.sunbird.org/learn/readme#what-is-sunbird-cokreat**](https://cokreat.sunbird.org/learn/readme#what-is-sunbird-cokreat)



### Front-end Libraries

Please refer the below for more details of front-end libraries.

[independent-libraries](../independent-libraries/ "mention")

### API Player

* Sunbird-Portal (API service)\
  Sunbird portal is packaged with Client & Server side applications. The server slide application(NodeJS) will get build & deployed independently which will act as proxy service for Sunird-Portal(UI) application.
* Sunbird-Creation-Portal (API service)\
  Sunbird creation portal is also packaged with Client & Server side applications. The server slide application(NodeJS) will get build & deployed independently which will act as proxy service for Sunird-Creation-Portal(UI) application.
* Form service

[form-service](workflows/form-service/ "mention")

* Contribute(Program) service

{% embed url="https://cokreat.sunbird.org/contribute/contribution-service" %}



### Dependant Sunbird BB's

[dependencies.md](../../use/learn-more/dependencies.md "mention")



