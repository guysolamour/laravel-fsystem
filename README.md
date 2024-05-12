# Laravel Administrable Ad

[![Packagist](https://img.shields.io/packagist/v/guysolamour/laravel-fsystem.svg)](https://packagist.org/packages/guysolamour/laravel-fsystem)
[![Packagist](https://poser.pugx.org/guysolamour/laravel-fsystem/d/total.svg)](https://packagist.org/packages/guysolamour/laravel-fsystem)
[![Packagist](https://img.shields.io/packagist/l/guysolamour/laravel-fsystem.svg)](https://packagist.org/packages/guysolamour/laravel-fsystem)

This package is an ad management extension for the manageable package.

This package is an extension of the package - [laravel-administrable](https://github.com/guysolamour/administrable) and cannot be used outside of it.
For the complete documentation [it's here](https://guysolamour.github.io/laravel-administrable/).


## Installation

Install via composer
```bash
composer require guysolamour/laravel-fsystem
```

## Utilisation

This package is an extension for larevel fileystem class

```php
use Guysolamour\Fsystem\Fsystem;

$fsystem = new Fsystem();
$fystem->allFiles(database_path());

```

## Security

If you discover any security related issues, please email rolandassale@gmail.com
instead of using the issue tracker.

## Credits

- [Guy-roland ASSALE](https://github.com/guysolamour/laravel-fsystem)
- [All contributors](https://github.com/guysolamour/laravel-fsystem/graphs/contributors)

This package is bootstrapped with the help of
[melihovv/laravel-package-generator](https://github.com/melihovv/laravel-package-generator).
