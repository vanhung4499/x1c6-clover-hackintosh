<h1 align="center"> Hackintosh the Thinkpad X1 Carbon 6th Generation Using Clover </h1>

<p align="center">
<a href="https://www.apple.com/macos/big-sur/">
  <img src="https://img.shields.io/badge/macOS-Big_Sur_v11.4-red.svg"/> </a>
<a href="https://pcsupport.lenovo.com/us/en/products/laptops-and-netbooks/thinkpad-x-series-laptops/thinkpad-x1-carbon-6th-gen-type-20kh-20kg/downloads/driver-list/component?name=BIOS%2FUEFI">
  <img src="https://img.shields.io/badge/Model-20KH*-9cf"/> </a>
<a href="https://github.com/CloverHackyColor/CloverBootloader/">
  <img src="https://img.shields.io/badge/Clover-12AED6"/> </a>
</p>

<p align="center">
<a href="https://www.facebook.com/vnohackintosh/">
   <img src="https://img.shields.io/badge/Facebook-VNOHackintosh-informational?style=flat&logo=facebook&logoColor=white&color=3a4dc9"> </a>
<a href="https://www.facebook.com/vanhung4499/">
   <img src="https://img.shields.io/badge/Facebook-vanhung4499-informational?style=flat&logo=facebook&logoColor=white&color=3a4dc9"> </a>
<a href="">
</p>

<p align="center">
<a href="https://vanhung4499.github.io/x1c6-clover-hackintosh/">
  <img src="https://raw.githubusercontent.com/vanhung4499/x1c6-clover-hackintosh/master/assets/x1c6.png" alt="Thinkpad X1 Carbon 6th Gen" width="400">
</p>

### Computer Spec:

| Component        | Brank                              |
| ---------------- | ---------------------------------- |
| CPU              | Intel i7 8650U                     |
| iGPU             | Intel UHD620                       |
| Lan              | Intel I219-LM                      |
| Audio            | Realtek ALC285                     |
| Ram              | 16 GB LPDDR3 2133 Mhz              |
| Wifi + Bluetooth | BCM943602CS + adapter              |
| NVME             | SAMSUNG 970 EVO PLUS 250 GB        |
| SmBios           | MacBookPro 15,2                    |
| BootLoader       | Clover 5139                        |
| macOS            | Big Sur 11.5.2                     |

![clover](./assets/clover.png)

### What works and What doesn't or WIP:

- [x] Intel UHD620 iGPU with Backlight
- [x] Intel UHD620 iGPU HDMI Output
- [x] ALC285 Audio (Speaker, HP, Jack)
- [x] All USB-A and USB-C Ports
- [x] SpeedStep / Sleep / Wake
- [x] HID Key PWRB & SLPB 
- [x] Synaptics SMBus Touchpad with gesture
- [x] Keyboard (PS2-Internal) with backlight
- [x] All FN Key
- [x] Wi-Fi and Bluetooth BCM943602CS (with adapter)
- [x] Intel I219-LM 
- [x] SSD NVME Slot-2 PciE Gen3x4 
- [x] Micro SD Cardreader (USB-Internal)
- [x] WebCam (USB-Internal)
- [x] All Sensors CPU, IGPU, BATTERY, NVME, FAN
- [x] ACPI Battery
- [x] NVRAM (Native)
- [x] Dualboot with Windows 11

## Installation

When I use X1C6 Opencore EFI from [Tylernguyen repos](https://github.com/tylernguyen/x1c6-hackintosh), Windows crash after 2 minutes, so I switched from opencore to clover.

All ACPI files are taken from his repos, I modified some hotpatch.

Please follow his guide to install macOS to SSD!

## Credits

- [Apple](https://apple.com) for macOS.
- [Acidanthera](https://github.com/acidanthera) for OpenCore and all the lovely hackintosh work.
- [Tylernguyen](https://github.com/tylernguyen/x1c6-hackintosh) for his x1c6 opencore repos
For great and detailed guides.
- [VNOHackintosh](https://facebook.com/vnohackintosh) Support group for installation and post installation.
