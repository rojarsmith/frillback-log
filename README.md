Frillback Developer Log
===

This is the log about developing Frillback.

The project is the enterprise cloud ecosystem by micro service.

- Service Register Service
  Micro service architecture.

  Monitor service health.

  Service redundance.

- Member Register ServiceMember can register the account.

  High security resist the most of hacker attack.

  Support Email, SMS verify.

  Support API.

  Support web UI backend.

- OTA Service

  Member can management firmware.

  Support multi-segment transport.

  Support fetch file with hash key without login.

  Support multi-country CDN.

  Support API.

  Support web UI backend.

This is the close source business project. 

------

Revision: 6f9942d0255bae0ba99a736efb71762a4f044674
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 6/4/2021 8:32:36 AM
Message:
Fixed Unresolved dependency: org.projectlombok lombok. Version number is requirement in sub project.


Revision: 1ba08f6f4a907d796b7714350cc0375e4b3de91d
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 6/2/2021 4:36:56 PM
Message:
Add the config of logging.


Revision: 15843a646e02a48e16b24109a8a362bcea39a75b
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 6/2/2021 3:52:24 PM
Message:
Build the template for call the shared function at frillback-core project using Gradle.


Revision: 843302fc3d7ef20035a887c3f91504c2436b3ab4
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 6/2/2021 2:58:55 PM
Message:
Porting ValueValidate main code and test code to frillback-core.


Revision: 2d5d0b384f8a6d732ac8665435d6bc39f2613808
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 6/2/2021 2:36:54 PM
Message:
Add the frillback-core for base code.


Revision: 13c794e6aa4e52f5a8a164d9f2eeb3f5e8c52b77
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 5/27/2021 5:10:34 PM
Message:
Update log.


Revision: 83f4579cc5411262f62ec53459a3b0e55ea8bfc8
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 5/27/2021 5:09:01 PM
Message:
Kafka consumer group-id is not required for producer.


Revision: c8165981d957e0602f9a6410e134e5882b352418
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 5/27/2021 4:58:58 PM
Message:
Add the template for multi consumer subscribe 1 topic.


Revision: 787ba66a228fcbbc486f1b843e78fcf439f72dae
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 5/27/2021 3:32:29 PM
Message:
Add the project device-management for device management.


Revision: f202ecc941787e27de82ca754a2771fb3bfb520f
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 5/27/2021 1:49:18 PM
Message:
Build the template to send and listen Kafka.


Revision: 8216cd33ece7258d6ff30393dfbfc5339fe7d496
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 5/26/2021 4:01:13 PM
Message:
Add the crypto-wallet project for welfare.


Revision: 8d12e4345e1252fe64f19179d56e9a1a528e8f1c
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 5/25/2021 2:37:26 PM
Message:
Add the user-center for user register or personal management.


Revision: e6cfc01b5f34e1d49c2a36c7d612f3c8999d903d
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 5/25/2021 12:13:46 PM
Message:
Integrate logback for service-registration service.


Revision: d893200fd131f6fa12cdec5c7039213160430b10
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 5/25/2021 11:08:39 AM
Message:
Add the template of notice mail.


Revision: 32c47bb6d1d2133912b836dbb1b705e0b47c8f8a
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 5/24/2021 4:27:48 PM
Message:
Add EurekaInstanceRenewedEvent, EurekaRegistryAvailableEvent, EurekaServerStartedEvent listener.


Revision: 06561fd24c45d50edb55601d78a2bf1d30cc4d67
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 5/24/2021 4:07:00 PM
Message:
Add EurekaInstanceRegisteredEvent listener.


Revision: 56d9cae7bac1d961f246aa6971bf82c7434352b3
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 5/24/2021 3:54:14 PM
Message:
Add the first developer log.


Revision: 304c25a068570edc7ec8f69067e7032d6a63e5e2
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 5/24/2021 3:46:55 PM
Message:
Add EurekaInstanceCanceledEvent listener.


Revision: b6d72c7d0e17a649ee7aede85e611d04bce1888b
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 5/24/2021 2:24:46 PM
Message:
SpringCloud 2.0 change the config name ipAddress to ip-address.


Revision: f10ffbecd1223423f3a2e3a57a79feb9f95eb3f4
Author: Rojar Smith <rojarsmith@gmail.com>
Date: 5/24/2021 2:11:17 PM
Message:
Add eureka project.
