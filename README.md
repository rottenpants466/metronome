<div>
    <h1 align="center">Metronome</h1>
    <h3 align="center"><img src="data/icons/com.github.artemanufrij.metronome.svg"/><br>A simple metronome</h3>
    <p align="center">Designed for <a href="https://elementary.io">elementary OS</p>
</div>

[![Build Status](https://travis-ci.org/artemanufrij/metronome.svg?branch=master)](https://travis-ci.org/artemanufrij/metronome)

### Donate
<a href="https://www.paypal.me/ArtemAnufrij">PayPal</a> | <a href="https://liberapay.com/Artem/donate">LiberaPay</a> | <a href="https://www.patreon.com/ArtemAnufrij">Patreon</a>

<p align="center">
  <a href="https://appcenter.elementary.io/com.github.artemanufrij.metronome">
    <img src="https://appcenter.elementary.io/badge.svg" alt="Get it on AppCenter">
  </a>
</p>
<p align="center">
  <img src="Screenshot.png"/>
</p>

## Install from Github.

As first you need elementary SDK
```
sudo apt install elementary-sdk
```

Install dependencies
```
sudo apt install libgstreamer1.0-dev
```

Clone repository and change directory
```
git clone https://github.com/artemanufrij/metronome.git
cd metronome
```

Compile, install and start Metronome on your system
```
meson build --prefix=/usr
cd build
sudo ninja install
com.github.artemanufrij.metronome
```
