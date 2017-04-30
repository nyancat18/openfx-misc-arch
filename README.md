# OpenFX module

This is a VFX pack for Natron

Table of Contents
* [Download](#download)
* [Building](#building)
    * [OptDeps](#OptDeps)
    * [Build flags](#build-flags)
* [Credits](#credits)
* [License](#license)
* [Donations](#donations)



## Download
* **Arch Linux**:
Pre-built binaries are hosted in the AUR: [OpenFX](https://aur.archlinux.org/packages/openfx-misc/)

## Building

*The build process takes about ½ hour on a shitty pc and 10 min with a good hardware, i5-3550 CPU @ 3.90GHz and 16GB ram. (without ccache)*



### OptDeps

##### firejail-extras
Lets you run Natron at an isolated, network-less enviorment, without run an expensive VM.

##### natron-plugins
A set of python plugins

##### natron-openfx-gmic-bin
Lets you use the GMIC API at Natron

### Build flags
make CONFIG=release

## Credits
* [OpenFX](https://github.com/devernay/openfx-misc)


## License
GPLv3. See [LICENSE](LICENSE)

## Donations
Donations are welcome and keep me motivated :-)
* BTC: `14W89mnv7pCPqLYHAevWa4PWq9efnHupqK`
* LTC: `LXmmXg6FEVs4nLy8MFTzRZhESARA2EwUbX`
