# Configuration

Yii 3 application does not have dedicated configuration and is configured via Dependency Injection container. There are
multiple ways configuring your application. We will focus on concepts used in default project template first and then
will provide additional ways one may configure the framework.

## Composer Config Plugin

In the application template [hiqdev/composer-config-plugin](https://github.com/hiqdev/composer-config-plugin) is used.
What the plugin does is collecting configs specified in all dependencies `composer.json`, `config-plugin` section and
merging them.

## Dependency Injection Container


