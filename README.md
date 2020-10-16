# Amazon Selling Partner API Client for PHP

## Requirements

PHP 5.5 and later

## Installation & Usage

### Composer

To install the bindings via [Composer](http://getcomposer.org/), add the following to `composer.json`:

```
{
  "repositories": [
    {
      "type": "git",
      "url": "https://github.com/udx/amazon-sp-client-php.git"
    }
  ],
  "require": {
    "udx/amazon-sp-client-php": "*@dev"
  }
}
```

Then run `composer install`

### Manual Installation

Download the files and include `autoload.php`:

```php
    require_once('/path/to/./vendor/autoload.php');
```

## Tests

To run the unit tests:

```
composer install
./vendor/bin/phpunit
```

## [Documentation](docs)
