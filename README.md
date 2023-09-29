# RyzenTosh
OpenCore EFI for B450 Chipset Motherboard with AMD Ryzen 5 2600G Processor + Radeon™ RX 6600 XT Dedicated Graphics.

## Specification

- Motherboard     : Asus TUF B450-PLUS Gaming
- CPU       : AMD Ryzen 5 2600G with Radeon Graphics
- RAM       : 4 x 8GB DDR4 3000Mhz
- Storage   : 500GB NVME SSD
- dGPU      : MSI Mech Radeon™ RX 6600 XT Dedicated Graphics
- Wifi      : Fenvi FV-T919 (BCM4360) (Requires OCLP)
- Audio     : Realtek ALC892
- Boot Mode : UEFI
- Bootloader : OpenCore 0.9.5
- OS : macOS Sonoma 14.0 + Ubuntu 22.04.3 LTS

## What Works?

- QE/CI Graphics of RX 6600 XT + DRM
- CPU Power Management
- Shutdown and Restart
- All USB Ports
- HDMI
- Audio (Rear & Front)
- TRIM Support for SSD
- Airdrop
- Etc

## WIP
- Camera Continuity


## Tutorial
- From Zero Tutorial : https://dortania.github.io/OpenCore-Install-Guide/
- Creating the USB Installer : https://dortania.github.io/OpenCore-Install-Guide/installer-guide/
- Generating SMBIOS : https://github.com/corpnewt/GenSMBIOS
- USB Fixes : https://dortania.github.io/OpenCore-Post-Install/usb/ and https://github.com/usbtoolbox/tool

Tutorial on "USB Fixes" related to the UTBMap.kext and SSDT-SLEEP.aml files. Please pay close attention to the guidelines that have been provided.

All kinds of errors and kernel panics, beyond my responsibility.

## Results
[![Ventura_13.4.jpg](https://github.com/klabit87/Personal_Ryzentosh/blob/main/screenshots/Ventura_13.4.jpg)](https://github.com/klabit87/Personal_Ryzentosh/blob/main/screenshots/Ventura_13.4.jpg)


[![Sonoma_14.0.jpg](https://github.com/klabit87/Personal_Ryzentosh/blob/main/screenshots/Sonoma_14.0.jpg)](https://github.com/klabit87/Personal_Ryzentosh/blob/main/screenshots/Sonoma_14.0.jpg)
