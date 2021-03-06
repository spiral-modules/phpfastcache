# PHPFastCache PSR6 and PSR16 adapters
[![Latest Stable Version](https://poser.pugx.org/spiral/phpfastcache/v/stable)](https://packagist.org/packages/spiral/phpfastcache)
[![Total Downloads](https://poser.pugx.org/spiral/phpfastcache/downloads)](https://packagist.org/packages/spiral/phpfastcache)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/spiral-modules/phpfastcache/badges/quality-score.png)](https://scrutinizer-ci.com/g/spiral-modules/phpfastcache/)
[![Coverage Status](https://coveralls.io/repos/github/spiral-modules/phpfastcache/badge.svg)](https://coveralls.io/github/spiral-modules/phpfastcache)
[![Build Status](https://travis-ci.org/spiral-modules/phpfastcache.svg?branch=master)](https://travis-ci.org/spiral-modules/phpfastcache)

Spiral utilizes PSR-16 (ORM) and PSR-6 (psr7-middlewares) protocols to allow your application to communicate with cache engines.

## Installation
```
composer require spiral/phpfastcache
spiral register spiral/phpfastcache
```

## Existed Bridges
Take a look at existed module `spiral/phpfastcache` which creates bridge to [https://github.com/PHPSocialNetwork/phpfastcache](https://github.com/PHPSocialNetwork/phpfastcache) library and adds cache configuration into your application.

`composer require spiral/phpfastcache`
`spiral register spiral/phpfastcache`

Add bootloader `Spiral/PhpFastCache/CacheBootloader` to enable caching.
