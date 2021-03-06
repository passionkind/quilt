# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## ? - ?

### Fixed

- Added `prefix` parameter to redirect statement in `create-enable-cookies` to conform with default redirect handling

## 3.1.37 - 2019-09-23

### Fixed

- No longer errors out on fresh installs with no session [1022](https://github.com/Shopify/quilt/pull/1022)

## 3.1.36 - 2019-08-30

### Fixed

- Package no longer allows sessions from one shop to bleed over into another [940](https://github.com/Shopify/quilt/pull/940)

## 3.1.32 - 2019-08-15

### Fixed

- Package now lists missing '@shopify/network' dependency [862](https://github.com/Shopify/quilt/pull/862)

## 3.1.31 - 2019-08-13

### Fixed

- Installation no longer fails if accessToken is invalid [#844](https://github.com/Shopify/quilt/pull/844)

## 3.1.14 - 2019-02-05

### Fixed

- OAuth route no longer rejects uppercase shop domains [#493](https://github.com/Shopify/quilt/pull/493)

## 3.1.11 - 2019-01-10

### Fixed

- HMAC validation no longer breaks when params are unsorted [#451](https://github.com/Shopify/quilt/pull/451)

## 3.1.10 - 2019-01-09

- Start of Changelog
