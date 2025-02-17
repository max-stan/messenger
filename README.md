# messenger
Simple Magento 2 extension that help you send messages to your friends!

## Features 
- Send messages to your friends
- Change,
- Create or 
- Delete customer messages from the admin panel
- REST, SOAP APIs and additional GraphQl extension

## Installation
Extension requires **Magento 2.4+ version**

```sh
cd [magento_installation_path]
git clone https://github.com/Maxikkkk/messenger
composer config repositories.messenger path ./messenger/profstep-messages
composer require profstep/module-messages
bin/magento mod:en ProfStep_Messages
```
For GraphQl extension
```sh
composer config repositories.messenger-graph-ql path ./messenger/profstep-messages-graph-ql
composer require profstep/module-messages-graph-ql
bin/magento mod:en ProfStep_MessagesGraphQl
```

## Uninstall

```sh
cd [magento_installation_path]
bin/magento mod:dis ProfStep_Messages
composer config --unset repositories.messenger
composer remove profstep/module-messages
```
For GraphQl extension
```sh
cd [magento_installation_path]
bin/magento mod:dis ProfStep_MessagesGraphQl
composer config --unset repositories.messenger-graph-ql
composer remove profstep/module-messages-graph-ql
```
## React App
This extension can be integrates with [React App](https://github.com/Maxikkkk/react-messenger).
