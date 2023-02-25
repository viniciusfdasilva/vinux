
<p align="center">
<h3>Welcome to Vinux!</h3>
</p>

<p align="center">
<img src="vinux.png">
</p>

*******************************************************
<p align="center">
<h4>Portable Operating System based on Linux Kernel</h4>
</p>

*******************************************************

Version: 0.2

Author: Vinicius F da Silva

Github: https://github.com/viniciusfdasilva

Source Code: https://github.com/viniciusfdasilva/vinux

*******************************************************
# Installation

To install Vinux OS, you need install a QEMU emulator

###### ArchLinux:
```console
$ pacman -S qemu
```

###### Debian:
```console
$ apt-get install qemu
```

###### Gentoo:
```console
$ emerge --ask app-emulation/qemu
```

###### CentOS:
```console
$ yum install qemu-kvm
```

###### SUSE:
```console
$ zypper install qemu
```

# Run

To run Vinux OS execute this command:

```console
$ qemu-system-x86_64 .../vinux/img/vinux.img
```


