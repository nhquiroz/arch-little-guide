# :penguin: Arch Little Guide

> Personal little [**`Arch Linux`**](https://www.archlinux.org/) guide.  

**`Disclaimer:`** I started using Arch recently and will update it as I learn, with info I find useful, **`just for my needs`**.

:warning: Always [**`read the Wiki`**](https://wiki.archlinux.org/) first!

## Contents

- [Useful commands](#useful-commands)
  - [pacman](#pacman)
  - [yaourt](#yaourt)
 - [System maintenance](#system-maintenance)
   - [downgrades](#downgrades)
   - [misc](#misc)

---

## Useful commands

### [pacman](https://wiki.archlinux.org/index.php/pacman)

- **`sudo pacman -S <package>`** – *install `<package>` from Arch repo.*  
- **`sudo pacman -R <package>`** – *uninstall `<package>`.*  
- **`sudo pacman -Syu`** – *sync and upgrade installed packages.*  
- **`sudo pacman -Syuw`** – *sync and download only (no installing).*  

### [yaourt](https://archlinux.fr/yaourt-en)

- **`yaourt <package>`** – *search and install `<package>`, with AUR support.*  
- **`yaourt -R <package>`** – *uninstall `<package>`.*  
- **`yaourt -Syu`** – *sync and upgrade installed packages, including AUR packages.*  
- **`yaourt -Syuw`** – *sync and download only (no installing), including AUR packages.*  

## System maintenance [**`(wiki)`**](https://wiki.archlinux.org/index.php/System_maintenance)

### downgrades

- Read about [**`downgrading packages`**](https://wiki.archlinux.org/index.php/downgrading_packages).  
- **`downgrade <package>`** – *downgrade conflictive package.*

### misc

- **`systemd-analyze blame`** – *find out which service takes how much time to finish during boot.*  
