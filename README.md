## Description

The official BlackArch Linux installer. You can run it on any Linux systems.
It is recommend to use it with Arch or BlackArch Linux ISOs though.

## Installation

On Arch Linux, run:
```sh
pacman -S blackarch-installer
```
On any other distribution follow these steps:

```bash
1) git clone https://github.com/BlackArch/blackarch-installer.git
2) cp -R blackarch-installer/ /usr/share/blackarch-installer
3) ln -sf /usr/share/blackarch-installer/blackarch-install /usr/bin/blackarch-install
4) chmod +x /usr/bin/blackarch-install
5) blackarch-install
```

## Usage

Simply run:
```sh
$ blackarch-install
```
and go ahead.

## Get Involved

You can get in touch with the BlackArch Linux team. Just check out the following:

**Please, send us pull requests!**

**Web:** https://www.blackarch.org/

**Mail:** team@blackarch.org

**IRC:** [irc://irc.freenode.net/blackarch](irc://irc.freenode.net/blackarch)
