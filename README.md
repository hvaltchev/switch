# Switch

![](https://img.shields.io/badge/switch-sx--os-red.svg)
![](https://img.shields.io/badge/switch-sdfiles-orange.svg)

## Installation

You can download the latest version in a zip file: https://github.com/GreatWizard/switch/archive/master.zip

Then extract the whole zip file at the root of your SD card.

## Content

### Homebrews

- [appstore v2.2](https://github.com/vgmoose/appstorenx): Switch App Store - download/manage homebrew apps for hbmenu
- [Checkpoint v3.7.4](https://github.com/BernardoGiordano/Checkpoint): Fast and simple homebrew save manager for 3DS and Switch
- [EdiZon v12.12.2019](https://github.com/thomasnet-mc/EdiZon): A save editor for Horizon by thomasnet and WerWolv
- [EdiZon ConfigAndScripts v18b0055](https://github.com/WerWolv98/EdiZon_ConfigsAndScripts): The official EdiZon Editor Config and Editor Script repository
- [ftpd v2.3.1](https://github.com/mtheall/ftpd): FTP Server
- [Goldleaf v0.8](https://github.com/XorTroll/Goldleaf): 🍂 Nintendo Switch multipurpose homebrew tool
- [Homebrew Menu v3.2.0](https://github.com/switchbrew/nx-hbmenu): The Nintendo Switch Homebrew Menu
- [JKSV v04.10.2020](https://github.com/J-D-K/JKSV):Data Dump/Restore tool for Switch
- [ldnmitm config v1.3.3](https://github.com/spacemeowx2/ldn_mitm)
- [NX-Shell v2.11](https://github.com/joel16/NX-Shell): 3DShell port for the Nintendo Switch
- [nxdumptool v1.1.8](https://github.com/DarkMatterCore/gcdumptool): Nintendo Switch Game Card Dump Tool
- [NXThemes Installer v2.3.1](https://github.com/exelix11/SwitchThemeInjector): A layout installer for the Nintendo Switch
- [SX Dumper v2.0.4R](https://sx.xecuter.com): Dump your retail game cartridges
- [Tinfoil v8.10R36](http://tinfoil.io): A homebrew game, update, and DLC installer

### Others

- [Switch Themes](https://suchmememanyskill.github.io/Themes/Switch_Themes/)

### Tools

- [XCI_Trimmer c51a186](https://github.com/AnalogMan151/XCI_Trimmer): Python3 script to trim and pad XCI ROM files
- [XCI-Explorer v1.5.0](https://github.com/StudentBlake/XCI-Explorer): View contents of XCI files and more

### CFW

#### SX OS

A Custom Firmware for Nintendo Switch.

- [Xecuter SX OS v3.0.2 beta](https://sx.xecuter.com/): Latest OFW supported: 10.0.4
- Run tinfoil instead of eShop (010000000000100B)
- [SX Autoloader 1.30 (00FF0012656180FF)](https://team-xecuter.com/community/resources/sx-autoloader.25/updates)

#### Atmosphère

Atmosphère is a work-in-progress customized firmware for the Nintendo Switch.

- [Atmosphère 0.11.1](https://github.com/Atmosphere-NX/Atmosphere): Latest OFW supported: 10.0.0
- ES and FS SIGPATCHES
- [ldn_mitm sysmodule v1.3.3 (4200000000000010)](https://github.com/spacemeowx2/ldn_mitm)
- Run tinfoil instead of eShop (010000000000100B)

#### hekate

Nintendo Switch Bootloader - CTCaer mod.

- [hekate - CTCaer mod v5.1.4 & Nyx v0.8.7](https://github.com/CTCaer/hekate): Latest OFW supported: 10.0.0

## Troubleshootings

### Mac and empty Homebrew Menu

> When booting into SX OS hbmenu I get the error "No applications could be found on the SD card. Make sure a folder named /switch exists in the root of the SD card and it contains applications.".

In order to fix it, run in a terminal:

```
sudo chflags -R arch /Volumes/<SDCARD>/switch
```
