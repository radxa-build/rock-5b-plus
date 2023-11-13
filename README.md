# ROCK 5B PLUS

[![Build image for Release channel](https://github.com/radxa-build/rock-5b-plus/actions/workflows/build.yml/badge.svg)](https://github.com/radxa-build/rock-5b-plus/actions/workflows/build.yml)[![Build image for Test channel](https://github.com/radxa-build/rock-5b-plus/actions/workflows/test.yml/badge.svg)](https://github.com/radxa-build/rock-5b-plus/actions/workflows/test.yml)

## What is this?

This repo is the central location for Radxa-built system images for ROCK 5B PLUS.

Not all images are officially supported by Radxa. Some of them are only provided as-is with no warranty. Please read below for detailed explanations.

## What images are provided?

Currently 4 flavors are provided:

- Debian KDE: This flavor is officially supported, tested, and recommended for all users.
- Debian CLI: This flavor is officially supported. This flavor is quite minimal and is intended for headless usage. We do not support desktop usage on top of this flavor.
- Ubuntu KDE: This flavor is provided as-is except for critical issues. Desktop is currently not working and we intend to fix it in a later time. This (currently broken) build is generated to catch build system issues.
- Ubuntu CLI: This flavor is provided as-is except for critical issues. Users should look at Debian CLI as an alternative.

Please also always use [the latest release](https://github.com/radxa-build/rock-5b-plus/releases/latest) instead of any pre-release / test builds. Those will not be supported.

## Help! Something doesn't work!

For other questions, please first take a look at [our Wiki](https://wiki.radxa.com/Rock5), which covers the most basic usages.

Should you have any additional questions, please visit [our forum](https://forum.radxa.com/) or [our Discord](https://rock.sh/go), and we are willing to help.
