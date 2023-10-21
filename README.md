# Dell-Latitude-5480-Monterey-i5-6th-gen-Success-EFI-Folder
Dell Latitude 5480 i5 6th Gen macOS Monterey, Everything Fully Working Success
<img width="1440" alt="Screenshot 2023-09-03 at 8 31 57 AM" src="https://github.com/mhussain800/Dell-Latitude-5480-Hackintosh-Monterey-EFI-i5-6th-Gen/assets/87897681/308cfc6c-9def-4f30-883c-737ddf5f23c2">
## **Laptop Specs!**
- Model: Dell Latitude 5480
- macOS Version: Monterey 12.6.8
- OpenCore Version: 0.9.4


+ CPU: Intel® Core™ i5-6200U
+ GPU: Intel® HD Graphics 520
+ RAM: 8GB DDR4
+ Ethernet: Intel® Ethernet I219-LM
+ Wi-Fi: Intel® Dual Band Wireless-AC 8265
+ Sound Card: ALC256 (ALC3246) (use layout-id 69 with ALC256.kext)
+ Trackpad: AlpsAlpine U1 Dual I2C Touchpad (0x120b)
+ SD Card Reader: Realtek RTS525A
+ Internal Display: 1920x1080 Full HD Screen
+ Runs Monterey perfectly 👌

# **✅ Whats working**
+ Wifi
+ Bluetooth
+ iGPU
+ All USB ports (3x USB 3.0, 1x USB-C)
+ Ethernet
+ Audio (using ALC256.kext with layout-id set to 69)
+ Headphone Jack with Mic
+ SD Card slot (using RealtekCardReader and RealtekCardReaderFriend)
+ Sleep & Wake with Lid (now works with USB mapping and GPRW and UPRW Instant Wake Patch)
+ CPU Power Management
+ iServices -iMessages,FaceTime,etc. (using this guide: https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html)
+ SMBUS
+ Microphone
+ Trackpad with MultiGestures (thanks to Juico's AlpsT4USB - which is now blankmac's AlpsHID!)
+ Front Camera
+ HiDPi Screen Resolution
+ AirPlay
+ Battery Percentage
+ Brightness Keys
+ HDMI with Audio

# **❌ Not working**
+ Handoff, AirDrop and Apple Watch Unlock (until you use a Broadcom Wi-Fi card)
+ You tell me

## **Credits**
+ Apple for macOS
+ acidanthera for OpenCore, Lilu, WhateverGreen and AppleALC
+ Dortania for OpenCore Install Guide
+ RehabMan for USBInjectAll (without this kext i will not be able to map USB)
+ headkaze for Hackintool
+ cholonam, syscl and sinetek for Sinetek-rtsx (thanks for bringing my SD Card reader back to life)
+ 0xFireWolf for RealtekCardReader and RealtekCardReaderFriend (basically a better version of Sinetek-rtsx)
+ And special thanks to Văn Hùng Nguyễn (vanhung4499) for helping me with the touchpad fix (the hardest part)
