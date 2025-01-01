---
layout: default
parent: serialosc
title: setup
nav_order: 1
redirect_from: /setup/
---

## Setting up serialosc

### macOS

*Note: if you have an older installation of serialosc, please remove the `Monome` folder from `~/Library/Application Support`, as it will supersede the homebrew installation.*

Install via homebrew:

- install [homebrew](https://brew.sh) on your Mac
- execute `brew install serialosc` to install serialosc
- execute `brew services start serialosc` to start serialosc
- execute `brew services list` to confirm serialosc is running

Successful `brew services list` output looks like:

```
Name        Status    User     File
serialosc   started   <you>   ~/Library/LaunchAgents/homebrew.mxcl.serialosc.plist
```

If you need to stop the serialosc process, execute `brew services stop serialosc`. Note that if you stop the serialosc process it will **not** start again, even if your machine is restarted, until you execute `brew services start serialosc`.

### Windows

Download the serialosc [release](https://github.com/monome/serialosc/releases/latest) and run the installer. Be sure to restart your device afterward.

### Linux

- [linux setup guide](/docs/serialosc/linux)
- [compiling from source](/docs/serialosc/source)

