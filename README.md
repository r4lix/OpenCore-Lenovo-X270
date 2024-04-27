# OpenCore-Lenovo-X270  
This repo contains the files and scripts to install macOS Ventura on the Lenovo X270 20K5  
You need to patch your systems own [DSDT](https://dortania.github.io/Getting-Started-With-ACPI/ssdt-methods/ssdt-methods.html).  
SMBIOS : MacBookPro14.1 (MacBook Pro Retina, 13-inch, Mid-2017)  

![X270](X270.png)

# Update History
- [x] macOS 12.1
- [x] macOS 12.2
- [x] macOS 13.0
- [x] macOS 13.4
- [x] macOS 13.6.6

# Laptop's Hardware
- <b>Model</b>: Thinkpad X270
- <b>CPU</b>: Intel(R) Core(TM) i5-6200U CPU @ 2.40GHz
- <b>GPU</b>: Intel HD Graphics 520 1536Mo
- <b>RAM</b>: 8 GB 2133MHz DDR4
- <b>Screen</b>: 12,4" (1366x768)
- <b>Wi-Fi</b>: AC-8260
- <b>Camera</b>: 720p
- <b>Battery</b>: 6-cell with inside battery 

# Bios settings
<b>Security</b>
- `Security Chip` **Disabled**
- `Memory Protection -> Execution Prevention` **Enabled**
- `Virtualization -> Intel Virtualization Technology` **Enabled**
- `Virtualization -> Intel VT-d Feature` **Enabled**
- `Anti-Theft -> Computrace -> Current Setting` **Disabled**
- `Secure Boot -> Secure Boot` **Disabled**
- `Intel SGX -> Intel SGX Control` **Disabled**
- `Device Guard` **Disabled**

<b>Startup</b>
- `UEFI/Legacy Boot` **UEFI Only**
- `CSM Support` **No**

# What's Working?
- [x] Intel HD 520 Graphics (incuding graphics acceleration, spoofed to Intel HD 620)
- [x] CPU Power Management
- [x] Battery
- [x] All USB ports (You probably need to map your ports)
- [x] HDMI port (including HDMI Audio)
- [x] Intel Ethernet port
- [x] Realtek Audio (including headphones jack)
- [x] Internal camera (including Facetime)
- [x] Trackpad (including gestures)
- [x] Shutdown / Reboot / Sleep
- [x] Keyboard (incuding all fn Keys)
- [x] Wi-Fi & Bluetooth (including Apple services)
- [x] iMessage, FaceTime, App Store, iTunes Store (with valid smbios)
- [x] DRM support (iTunes Movies, Apple TV+, Amazon Prime and Netflix, and others)
- [x] SD Card Reader
- [x] Sleep / Wake (lid sleep and lid wake)

# What's not working ⚠️
- [x] Everything looks perfect for now 