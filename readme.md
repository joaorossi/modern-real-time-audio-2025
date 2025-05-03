# Modern Real-Time Audio Programming Course

This repository contains code examples and framework to be used along the course.

## Pre-requisites

**MacOS**:
 - [XCode](https://developer.apple.com/xcode/)
 - [Developer Command Line Tools](https://www.youtube.com/watch?v=sF9UszljnZU)
 - [CMake](https://cmake.org/) - Can also be installed with [Homebrew](https://formulae.brew.sh/formula/cmake)

**Windows**:
 - [MS Visual Studio](https://visualstudio.microsoft.com/vs/community/) (2019/2022) - Community Edition is free.
 - [Git Bash](https://gitforwindows.org/)
 - [CMake](https://cmake.org/)

**Linux**:
 - [Linux instructions](readme-linux.md)

**Nice to have**:
 - [VSCode](https://code.visualstudio.com/) - Alternative cross-platform IDE.
 - [Reaper](https://www.reaper.fm/download.php) - Fully featured DAW. Demo is free and fully functional.
 - [PluginDoctor](https://ddmf.eu/plugindoctor/) - Handy for audio/DSP debugging. Demo is free and fully functional.
 - [Surge](https://surge-synthesizer.github.io/) - FOSS synth, handy for quick testing in a DAW.
 - [SocaLabs Plugins](https://socalabs.com/) - Various useful free plugins, like osciloscope and tone generators.
 - [ASIO4ALL](https://asio4all.org/) - *Windows only*. In case you don’t have a soundcard with an ASIO driver.

## Cloning the Repository
If you have a [github account](https://docs.github.com/en/get-started/signing-up-for-github/signing-up-for-a-new-github-account) with a [SSH key setup](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account):
```
git clone --recurse-submodules git@github.com:joaorossi/modern-real-time-audio-2025.git
```
Otherwise, the `https` will also work.
```
git clone --recurse-submodules https://github.com/joaorossi/modern-real-time-audio-2025.git
```

## Build the example project
```
./configure.sh
./build.sh mfrtaa
```
