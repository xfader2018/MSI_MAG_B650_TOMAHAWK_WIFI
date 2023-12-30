

# MSI MAG B650 TOMAHAWK WIFI + AMD 7800X3D Hackintosh

![About](Docs/about.png)

# Current macOS

Current Version: macOS Ventura 13.6.3

# Hardware

| Type | Model                |
| :-------- | :------------------------- |
| **CPU** | AMD Ryzen 7 7800X3D |
| **Motherboard** | MSI MAG B650 TOMAHAWK WIFI |
| **Memory** | 32 GB (2x16GB) Corsair DDR5 7200Mhz CL34 |
| **Graphics** | AMD Radeon RX6600XT |
| **PSU** | Corsair SF750 |
| **Wifi/Bluetooth** | Fenvi FV-HB1200 with Broadcom Chipset |

# Working
- Audio
- Ethernet network
- CPU Power Management
- USB Ports
- Sleep/Wake
- Wifi/BT

# Not working
iGPU, disable this in your BIOS.

# BIOS Settings
Default settings with XMP enabled. Disable iGPU.

# SMBIOS
Use MacPro7,1 model and create your own serial info with [genSMBIOS](https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html#using-gensmbios)

# USB Port Mapping

USB-Port Mapping is done via `USBPorts.kext`:

See below pictures for mapping according included kext.

| Name | Location                | Mode      |
| :-------- | :------------------------- | :------   |
| HS01 | Front USB3 port 1 |USB 2.0|
| SS01 | Front USB3 port 1 |USB 3.2|
| HS02 | Front USB3 port 2 |USB 2.0|
| SS02 | Front USB3 port 2 |USB 3.2|
| HS03 | Onboard USB 2.0 Headers |USB 2.0|
| HS04 | Realtek USB Audio onboard |USB 2.0|
| HS05 | Rear Blue ports 1-4 |USB 2.0|
| HS06 | Rear USB-C port |USB 2.0|
| SS06 | Rear USB-C port |USB 3.2|
| HS07 | Rear Black port 1 |USB 2.0|
| HS08 | Rear Black port 2 |USB 2.0|
| SS09 | Rear Blue ports 1-4 |USB 3.2|
| HS10 | Rear Red port 1 |USB 2.0|
| SS10 | Rear Red port 1 |USB 3.2|
| HS11 | Rear Red port 2 |USB 2.0|
| SS11 | Rear Red port 2 |USB 3.2|
| HS12 | Rear Red port 3 |USB 2.0|
| SS12 | Rear Red port 3 |USB 3.2|


![backpanel](Docs/backpanel.jpg)
