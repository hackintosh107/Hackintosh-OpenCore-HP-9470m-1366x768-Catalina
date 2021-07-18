# Hackintosh-OpenCore-HP-9470m-1366x768-Catalina
OpenCore EFI bootloader for HP 9470m with 1366x768 resolution

# Specifications:
* CPU: Intel Core i5-3437U
* GPU: Intel HD Graphics 4000
* Resolution: 1366x768
* Audio: IDT 92HD91BXX
* Wi-Fi: Intel® Centrino® Advanced-N 6235
* Bluetooth: Intel Bluetooth 4.0
* Ethernet: Intel 82579LM
* Touchpad: Synaptics SMBus TouchPad
* Card reader:
  - JMicron Card Reader
  - Alcor Micro USB Smart Card Reader
* Fingerprint: Synaptics Fingerprint Sensors

# Version: 
* OpenCore: 0.7.1
* macOS: 10.15 (Catalina)

# BIOS settings:
* Boot mode: UEFI Hybrid
* SATA mode: AHCI

# Working:
- [x] Intel HD Graphics 4000
- [x] Sleep
- [x] Audio (using AppleALC.kext with layout-id = 13)
- [x] Internal microphone
- [x] External microphone
- [x] Touchpad (with multi gestures)
- [x] Battery indicator
- [x] Ethernet
- [x] Wi-Fi (using with HeliPort)
- [x] Bluetooth
- [x] Sidecar
- [x] CPU power management
- [x] Webcam
- [x] USB ports
- [x] Fn function keys
- [ ] Card reader
- [ ] Synaptics Fingerprint Sensors

# Not test:
* DisplayPort external port
* D-Sub external port

# Download HeliPort:
https://github.com/OpenIntelWireless/HeliPort/releases

# SMBIOS:
iMac16,1
 
# Note:
Don't use this EFI bootloader for 1600x900 resolution