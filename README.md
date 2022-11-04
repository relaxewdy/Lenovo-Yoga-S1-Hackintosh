<h1 align="center"> macOS on Lenovo Thinkpad Yoga S1 </h1>

<img align="center" src="https://github.com/yusufklncc/Lenovo-Thinkpad-Yoga-S1-Hackintosh/blob/main/macOS%20Lenovo%20Thinkpad%20Yoga%20S1.png">

<h4 align="center"> OpenCore config for Hackintosh Lenovo Thinkpad Yoga S1 </h4>

<p align="center">
<a href="https://www.apple.com/macos/monterey/">
  <img src="https://img.shields.io/badge/macOS-Monterey_v12.6-purple" width="215"/> </a>
<a href="https://github.com/acidanthera/OpenCorePkg/releases">
  <img src="https://img.shields.io/badge/OpenCore-0.8.5-9cf" width="155"/> </a>
<a href="https://github.com/yusufklncc/Lenovo-Thinkpad-Yoga-S1-Hackintosh/releases">
  <img src="https://img.shields.io/badge/release-EFI-blue.svg" width="115"/> </a>
</p>
<p align="center">
<a href="https://t.me/yusufklncc">
  <img src="https://img.shields.io/badge/-@yusufklncc-2CA5E0?logo=Telegram&logoColor=blue" width="150"/> </a>
<a href="https://www.youtube.com/c/yusufklncc">
  <img src="https://img.shields.io/badge/-@yusufklncc-lightgrey?logo=YouTube&logoColor=red" width="150"/> </a>
<a href="https://www.paypal.com/paypalme/sevenpay">
  <img src="https://img.shields.io/badge/-@sevenpay-2CA5E0?logo=PayPal&logoColor=red" width="140"/> </a>

## Contents
  - [Screenshots](https://github.com/yusufklncc/Lenovo-Thinkpad-Yoga-S1-Hackintosh#screenshot-)
  - [Original Hardware](https://github.com/yusufklncc/Lenovo-Thinkpad-Yoga-S1-Hackintosh#original-hardware--)
  - [macOS Update History](https://github.com/yusufklncc/Lenovo-Thinkpad-Yoga-S1-Hackintosh#macos-update-history)
  - [What's working](https://github.com/yusufklncc/Lenovo-Thinkpad-Yoga-S1-Hackintosh#whats-working--)
  - [What's not working](https://github.com/yusufklncc/Lenovo-Thinkpad-Yoga-S1-Hackintosh#whats-not-working--)
  - [What's you have to do](https://github.com/yusufklncc/Lenovo-Thinkpad-Yoga-S1-Hackintosh#what-you-have-to-do)
  - [Kexts Used](https://github.com/yusufklncc/Lenovo-Thinkpad-Yoga-S1-Hackintosh#kext-used)
  - [Credits](https://github.com/yusufklncc/Lenovo-Thinkpad-Yoga-S1-Hackintosh#credits)
  - [Donate](https://github.com/yusufklncc/Lenovo-Thinkpad-Yoga-S1-Hackintosh#-donate---ba%C4%9F%C4%B1%C5%9F-)

## Screenshot 📷
<details>
<summary>Big Sur & Mojave</summary>

![](https://github.com/yusufklncc/Lenovo-Thinkpad-Yoga-S1-Hackintosh/blob/main/BigSur.png)
![](https://github.com/yusufklncc/Lenovo-Thinkpad-Yoga-S1-Hackintosh/blob/main/Mojave.png)

</details>

## Original Hardware  💻

Type | Spec | Status
:---------|:---------|:----------
Model Name      | Lenovo Thinkpad Yoga S1 | ✅
CPU              | Intel(R) Core(TM) i7-4510U CPU @ 2.0GHz (max 3.10Ghz) Haswell | ✅
RAM           | 8 GB 2400 MHz DDR4 | ✅
Internal Graphics Card | Intel® HD Graphics 4400 | ✅
Wi-Fi             | Intel Wireless 7260 | ✅
Audio       | Conexant CX20751 | ✅

## macOS Update History

- ✅ macOS Monterey 12.6 
- ✅ macOS Monterey 12.3
- ✅ macOS Monterey 12.0.1
- ✅ macOS Big Sur 11.6.1
- ✅ macOS Big Sur 11.5.2
- ✅ macOS Big Sur 11.0.1

## What's working  💻
  
Type | Status
:---------|:---------
Turbo boost and CPU frequency stage |  ✅
Intel HD Graphics 4400              |  ✅
Brightness control                  |  ✅
Audio Conexant CX20751 (id:28)      |  ✅
3.5mm Combojack                     |  ✅
Intel 7260 Wi-Fi and Bluetooth, Handoff, iMessage...         |  ✅
USB 3.0 (with Port Map)        |  ✅
Touchpad (14 gestures are working)   |  ✅
Touchscreen with gestures           |  ✅
Battery status   |  ✅
Camera   |  ✅
Shutdown / Reboot   |  ✅
Fn shortcut keys   |  ✅
S3 Sleep / Wake   |  ✅

## What's not working  💻
  
Type | Status
:---------|:---------
Airdrop, Sidecar (Beacuse Intel Wi-Fi)   | ❌

## What You Have to Do?

Type | Status
:---------|:---------
SMBIOS Settings  | ⚠️ 
With OpenCore Configurator you should definitely set your SMBIOS settings because the config does not contain SMBIOS information MacBook Pro 11,1  | ⚠️

## Kext Used 
 
Kext | Info 
:---------|:---------
[Lilu](https://github.com/acidanthera/Lilu) | An open source kernel extension bringing a platform for arbitrary kext, library, and program patching throughout the system for macOS.
[VirtualSMC](https://github.com/acidanthera/VirtualSMC) | Advanced Apple SMC emulator in the kernel. Requires Lilu for full functioning.
[WhateverGreen](https://github.com/acidanthera/WhateverGreen) | Various patches necessary for certain ATI/AMD/Intel/Nvidia GPUs. This is needed for Intel HD 620.
[AppleALC.kext](https://github.com/acidanthera/AppleALC) | An open source kernel extension enabling native macOS HD audio for not officially supported codecs without any filesystem modifications.
[USBPorts](https://www.youtube.com/watch?v=rlTDHkPzjAk&t=654s) | Kext to inject mapped USB Ports.
[VoodooI2C](https://github.com/VoodooI2C/VoodooI2C) | VoodooI2C is a project consisting of macOS kernel extensions that add support for I2C bus devices.
[VoodooPS2Controller](https://github.com/acidanthera/VoodooPS2) | Contains updated Voodoo PS/2 Controller, improved Keyboard & Synaptics TouchPad.
[SMCBatteryManager](https://github.com/acidanthera/VirtualSMC) | a member of VirtualSMC that parses battery info.
[SMCLightSensor](https://github.com/acidanthera/VirtualSMC) | a member of VirtualSMC that activate light sensor.
[SMCProcessor](https://github.com/acidanthera/VirtualSMC) | a member of VirtualSMC that provides power info of processor temperature.
[ECEnabler](https://github.com/1Revenger1/ECEnabler) | Allows reading Embedded Controller fields over 1 byte long, vastly reducing the amount of ACPI modification needed (if any) for working battery status.	
[AirportItlwm](https://github.com/OpenIntelWireless/itlwm) | An Intel Wi-Fi Adapter Kernel Extension for macOS.	
[IntelBluetoothFirmware](https://github.com/OpenIntelWireless/IntelBluetoothFirmware) | Kernel Extension that uploads Intel Wireless Bluetooth Firmware to provide native Bluetooth in macOS.	
[BlueToolFixup](https://github.com/acidanthera/BrcmPatchRAM) | Injecting bluetooth firmware on Monterey+.
[CPUFriend](https://github.com/acidanthera/CPUFriend) | A Lilu plug-in for dynamic power management data injection.
[CPUFriendDataProvider](https://github.com/acidanthera/CPUFriend) | A CPUFriend plug-in for CPU power management.
[USBWakeFixup.kext](https://github.com/osy/USBWakeFixup) | This extension is a workaround for that issue by creating a fake ACPI device with the right wakeup params.	
[FeatureUnlock](https://github.com/acidanthera/FeatureUnlock) | Lilu Kernel extension for enabling: Sidecar, NightShift, AirPlay to Mac, Universal Control.
[RestrictEvents](https://github.com/acidanthera/RestrictEvents) | Lilu Kernel extension for blocking unwanted processes causing compatibility issues on different hardware and unlocking the support for certain features restricted to other hardware.

## Credits
  
 - [Dortania](https://dortania.github.io) for developing OpenCore.
 - [Apple](https://www.apple.com) for macOS.
 - [Acidanthera](https://github.com/acidanthera) for most of the kexts.
 - [RehabMan](https://github.com/RehabMan) for battery patches.
 - [Sniki](https://github.com/Sniki) for USB kext.
 - And anyone else that helped to develop and improve hackintoshing.

<h1 align="center"> Donate - Bağış </h1>
<p align="center">
<a href="https://github.com/yusufklncc/yusfklncc/blob/main/Donate%20-%20Ba%C4%9F%C4%B1%C5%9F.md">
  <img src="https://github.com/yusufklncc/yusfklncc/blob/main/Resources/Donate.png" width="300">
