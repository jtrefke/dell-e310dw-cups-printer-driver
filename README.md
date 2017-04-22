# Dell E310dw Laser Printer CUPS driver for Arch Linux

This is a `PCKBUILD` to be used with `pacman` in Arch linux, essentially the same package you would download from the [Arch User Repository (AUR)](https://aur.archlinux.org/) (the idea is to ultimately upload it there).

It uses the original [Dell E310dw linux printer drivers    package](https://downloads.dell.com/FOLDER03004762M/1/Printer_E310dw_Driver_Dell_A00_LINUX.zip), which are provided as RedHat (rpm) package, but places the files where Arch Linux wants them to be.

## Installation instructions

1. Download this package from GitHub
1. Within the directory on your computer execute:
  1. `makepkg`
  1. `sudo pacman -U dell-e310dw-3.2.0-1-x86_64.pkg.tar.xz`

If you want to learn more, you can find a detailed explanation on package installation on the [Arch Linux Wiki](https://wiki.archlinux.org/index.php/creating_packages#Creating_a_PKGBUILD):
