<p align="center"><img src="https://github.com/greywold/ephember/blob/main/eph_ember.png" width="125"></a>
<h1 align="center">EPH Controls for Home Assistant</h1>
<p align="center">This is an unofficial project that is not affiliated with EPH Controls</p>
<br />
[![Version](https://img.shields.io/github/v/release/LarsK1/hass_solvis_control?label=version)](https://github.com/LarsK1/hass_solvis_control/releases/latest)
[![Validate for HACS](https://github.com/LarsK1/hass_solvis_control/workflows/Validate%20for%20HACS/badge.svg)](https://github.com/LarsK1/hass_solvis_control/actions/workflows/hacs.yml)
[![Validate% with hassfest](https://github.com/LarsK1/hass_solvis_control/workflows/Validate%20with%20hassfest/badge.svg)](https://github.com/LarsK1/hass_solvis_control/actions/workflows/hassfest.yml)
[![Safe Code](https://github.com/LarsK1/hass_solvis_control/actions/workflows/github-code-scanning/codeql/badge.svg)](https://github.com/LarsK1/hass_solvis_control/actions/workflows/codeql.yml)


A custom, developmental, component to integrate the [EPH Control](https://www.ephcontrols.com/)'s [Ember](https://www.ephcontrols.com/range/gateway/) cloud platorm into Home Assistant.

Please note that EPH Controls may break functionality at any time.

## Safety Warnings

1. This integration communicates with the EPH Ember platform through unofficial REST API calls that can be broken or shut down at any time.
2. Automations are executed remotely and can be buggy.
3. Status updates are similarly fetched remotely and are not realtime
4. This code may be buggy and amateurish.

You should use the EPH Control's official Ember application for notifications and configuration of your system.
