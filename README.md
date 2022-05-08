
# Unofficial GE Proton deb package ![latest tag](https://badgen.net/github/tag/peshkopy/ge-proton-deb-package)

The goal of this project is to provide an easy way to install or update [GE Proton](https://github.com/GloriousEggroll/proton-ge-custom) with a deb package for Debian-based Linux distributions like Ubuntu or Linux Mint.

## Features

- One package per major version, each new minor version overwrites the previous one.
- All games using the same major version are automatically updated to the latest minor version.
- The update is done automatically.

## Installation

- Download the latest deb package from this [link](https://peshkopy.gitlab.io/debian-package-repo/pool/main/g/ge-proton-7/ge-proton-7_latest_all.deb).
- Stop Steam.
- Run ```sudo dpkg --install ge-proton-<full-version>_all.deb```
- Start Steam.
- Read the [GE Proton](https://github.com/GloriousEggroll/proton-ge-custom) project page for use.

## Update

- The update takes place at the same time as the other system packages.


## Removing

- Stop Steam.
- Run ```sudo dpkg --remove ge-proton-<major-version>```
- Start Steam.

## Notes

- In order to keep the project light, only modified GE Proton file (compatibilitytool.vdf) is versioned.
- Other GE Proton installs are not affected by the deb package.
- GE Proton is installed in the global directory ```/usr/share/steam/compatibilitytools.d/```
- [gitlab.com/peshkopy/debian-package-repo](https://gitlab.com/peshkopy/debian-package-repo) is the package repository.

## Contribution

- Go to [new issue](https://github.com/peshkopy/ge-proton-deb-package/issues/new) to help fix any bugs.
- Go to [new idea](https://github.com/peshkopy/ge-proton-deb-package/discussions/new?category=ideas) to share a thought that can make this project better.
