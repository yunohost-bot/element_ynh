<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/readme_generator
It shall NOT be edited by hand.
-->

# Element for YunoHost

[![Integration level](https://dash.yunohost.org/integration/element.svg)](https://dash.yunohost.org/appci/app/element) ![Working status](https://ci-apps.yunohost.org/ci/badges/element.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/element.maintain.svg)

[![Install Element with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=element)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Element quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Element is a new type of messaging app. You choose where your messages are stored, putting you in control of your data. It gives you access to the Matrix open network, so you can talk to anyone. Element provides a new level of security, adding cross-signed device verification to default end-to-end encryption.

**Shipped version:** 1.11.58~ynh1

**Demo:** https://app.element.io/

## Screenshots

![Screenshot of Element](./doc/screenshots/homepage-all-platforms-1_1.png)

## Documentation and resources

* Official app website: <https://element.io>
* Official admin documentation: <https://element.io/help>
* Upstream app code repository: <https://github.com/element-hq/element-web>
* YunoHost Store: <https://apps.yunohost.org/app/element>
* Report a bug: <https://github.com/YunoHost-Apps/element_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/element_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/element_ynh/tree/testing --debug
or
sudo yunohost app upgrade element -u https://github.com/YunoHost-Apps/element_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>