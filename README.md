#PHPUnit Selenium 2

##Install

Create a file composer.json with the following content:
    
```json 
{
    "require": {
        "phpunit/phpunit-selenium": ">=1.2"
    }
}
```

Use Composer commands:

[Using Composer](https://getcomposer.org/doc/00-intro.md#downloading-the-composer-executable)
[Install Composer to Windows](https://getcomposer.org/doc/00-intro.md#using-the-installer)

```bash
composer install
```

##Testing

Downloading Selenium Standalone Server in:
    http://docs.seleniumhq.org/download/

Running server Selenium:
    mv downloads/selenium-server-standalone-2.48.2.jar /usr/local/bin
    java -jar selenium-server-standalone-2.48.2.jar

```bash
cd vendor/bin
phpunit TestLogin
```