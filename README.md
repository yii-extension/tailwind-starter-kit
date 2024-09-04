<p align="center">
    <a href="https://github.com/yii-extension" target="_blank">
        <img src="https://lh3.googleusercontent.com/ehSTPnXqrkk0M3U-UPCjC0fty9K6lgykK2WOUA2nUHp8gIkRjeTN8z8SABlkvcvR-9PIrboxIvPGujPgWebLQeHHgX7yLUoxFSduiZrTog6WoZLiAvqcTR1QTPVRmns2tYjACpp7EQ=w2400" height="100px">
    </a>
    <h1 align="center">Yii Extension Tailwind.</h1>
</p>
<p align="center">
    <a href="https://packagist.org/packages/yii-extension/tailwind"><img src="https://img.shields.io/packagist/dt/yii-extension/tailwind" alt="Total Downloads"></a>
    <a href="https://github.com/yii-extension/tailwind/actions?query=workflow%3Abuild"><img src="https://github.com/yii-extension/tailwind/workflows/build/badge.svg" alt="Build Status"></a>
    <a href="https://codecov.io/gh/yii-extension/tailwind"><img src="https://codecov.io/gh/yii-extension/tailwind/branch/master/graph/badge.svg?token=mFwYEYMr15" alt="Code Coverage"></a>
    <a href="https://dashboard.stryker-mutator.io/reports/github.com/yii-extension/tailwind/master"><img src="https://img.shields.io/endpoint?style=flat&url=https://badge-api.stryker-mutator.io/github.com/yii-extension/tailwind/master" alt="Mutation Testing"></a>
    <a href="https://github.com/yii-extension/tailwind/actions/workflows/static.yml"><img src="https://github.com/yii-extension/tailwind/workflows/static%20analysis/badge.svg" alt="Static Analysis"></a>
    <a href="https://shepherd.dev/github/yii-extension/tailwind"><img src="https://shepherd.dev/github/yii-extension/tailwind/coverage.svg" alt="Type Coverage"></a>
    <a href="https://packagist.org/packages/yii-extension/tailwind"><img src="https://img.shields.io/badge/license-BSD_3_Clause-green" alt="License"></a>
</p>



## Installation

```shell
composer require yii-extension/tailwind
```
## Widgets usage

The widgets do not register any assets, you must register the assets for [Tailwind Css Framework](https://github.com/yii-extension/asset-tailwind)

We will quickly and easily describe how to use widgets, and be able to use all the power of the Tailwind CSS framework with php.

- [Colors](docs/colors.md)
- [Dropdown](docs/dropdown.md)
- [Navbar](docs/navbar.md)

## Unit testing

The package is tested with [PHPUnit](https://phpunit.de/). To run tests:

```shell
./vendor/bin/phpunit
```

## Mutation testing

The package tests are checked with [Infection](https://infection.github.io/) mutation framework. To run it:

```shell
./vendor/bin/infection
```

## Static analysis

The code is statically analyzed with [Psalm](https://psalm.dev/docs). To run static analysis:

```shell
./vendor/bin/psalm
```

## License

The `yii-extension/tailwind` for Yii Packages is free software.

It is released under the terms of the BSD License. Please see [`LICENSE`](./LICENSE.md) for more information.

Maintained by [Yii Extension](https://github.com/yii-extension).

## Support the project

[![Open Collective](https://img.shields.io/badge/Open%20Collective-sponsor-7eadf1?logo=open%20collective&logoColor=7eadf1&labelColor=555555)](https://opencollective.com/yiisoft)

## Powered by Yii Framework

[![Official website](https://img.shields.io/badge/Powered_by-Yii_Framework-green.svg?style=flat)](https://www.yiiframework.com/)
