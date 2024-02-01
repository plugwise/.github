# Plugwise

## Community development and Support for Plugwise Products

Networked Plugwise products (i.e. Smile (Anna/Adam/P1) or Stretch):

- Smile python [plugwise](https://github.com/plugwise/python-plugwise) module
- Home Assistant Core [integration](https://www.home-assistant.io/integrations/plugwise/) / [source](https://github.com/home-assistant/core/tree/dev/homeassistant/components/plugwise)
- `custom_component` [plugwise-beta](https://github.com/plugwise/plugwise-beta)

USB Plugwise product (i.e. Stick): 

- USB python [plugwise_usb](https://github.com/plugwise/python-plugwise-usb) module
- `custom_component` [plugwise_usb-beta](https://github.com/plugwise/plugwise_usb-beta), 

Note: Versions up to `v0.34.10` of `plugwise-beta` support both Smile and Stick

Included in these repositories are a python [plugwise](https://github.com/plugwise/python-plugwise) module, published to [pypi](https://pypi.org/project/plugwise/) for use in your projects though mainly focussed on support for [Home Assistant (Core)](https://github.com/home-assistant/core). Pending inclusion of USB support for Plugwise into HA-Core and for development purposes we offer a `custom_component` through [plugwise-beta](https://github.com/plugwise/plugwise-beta).

Smile Module (python) providing interfacing with the Networked Plugwise devices:

- [x] Adam
  - [x] Lisa
  - [x] Jip
  - [x] Floor
  - [x] Tom
  - [x] Koen (a Koen always comes with a Plug, the Plug is the active part)
  - [x] Plug
  - [x] Aqara Plug
- [x] Anna
- [x] Smile P1
- [x] Stretch

USB Module (python) providing interfacing with USB Plugwise Device:

- [x] Stick
  - [x] Circle+ / Stealth+
  - [x] Circle / Stealth
  - [x] Scan
  The devices listed below have **NOT** been tested and are therefore unknown for their correct operation
    - [x] Sense
    - [x] Switch

Overall Status:

- [x] [Home-Assistant](https://home-assistant.io) via
  - [x] Native supporting networked Plugwise products
  - [ ] Native supporting USB Plugwise products (in progress)
  - [x] [HACS](https://hacs.xyz) and `custom_component` [Plugwise-HA](https://github.com/plugwise/plugwise-beta/) (supporting all devices above)

## Thanks / About us

Main team consists of @bouwew (mainly Smile), @brefra (USB), @compatech (Overall and Smile) and @dirixmjm (USB) - supported by helpful additions and reports from many community members! On the HA-Core team we also have @frenck as code-owner for the Smile integration.

On behalf all of us, big thanks to Plugwise and community members @riemers and @tane from HAshop for their support and obviously all our users and testers who dealt with our typos and challenges. Disclaimer, while we are communicating with Plugwise and they expressed their gratitude through their newsletter, we are not part of Plugwise as a company. We are just a bunch of guys anxious to get our (and your) Plugwise products working with Home Assistant.

Also we would like to thank the Core team (for a fantasic Home Assistant), Github for providing the means and ends to develop and maintain our code and @renovatebot [renovatebot/renovate](https://github.com/renovatebot/renovate) for keeping our dependencies in check. Codecov and CodeFactor also make sure we are kept in check, with all the previously mentioned together ensuring we deliver good quality code.
