# Introduction

This repository provides an aw88399-acf firmware package build script for Arch Linux to fix Linux audio on the Lenovo Legion Pro 7i Gen 10 (16IAX10H) and similar devices.

For pre-built Arch packages, please refer to [imitoy/linux-legion-audio-fix](https://github.com/imitoy/linux-legion-audio-fix).

# URL
Firmware: [nadimkobeissi/16iax10h-linux-sound-saga](https://github.com/nadimkobeissi/16iax10h-linux-sound-saga/blob/main/fix/firmware/aw88399_acf.bin)

# Instructions 

1. Clone this repository.
   ```bash
   git clone https://github.com/imitoy/aw88399_acf-PKGBUILD.git
   cd aw88399_acf-PKGBUILD
   ```

2. Build & Install
   ```bash
   makepkg -si
   ```

3. Reboot
   ```bash
   reboot
   ```
