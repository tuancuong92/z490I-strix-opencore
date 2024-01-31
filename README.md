Hackintosh ASUS ROG Strix Z490-I Gaming
========================================

- RTC fixed
- Airdrop, Handoff not work
- LAN in Sonoma Must be config by other way than Dortania's
- iServices only work when Wifi and LAN are fixed
- Bluetooth fixed with custom build of IntelBluetoothFirmware kext. Checkout the repo's pull request


Specs:
----------------
 - CPU: Intel Core i9 - 10900
 - RAM: Kingmax 32GB 3200MHz
 - GPU: Radeon RX 570 4GB
 - LAN: Intel I225-V
 - Bluetooth: Intel
 - Wifi: YUNCLOUD USB Wifi 1900Mbps (RTL8814AU)
 - OpenCore version: 0.9.6
 - macOS: 14.3
 - Case: CoolerMaster MasterBox NR200

Notes:
--------------
- Config your own SMBios info
- USB Map is optimized for Motherboard and my own use-caseses, remap if 
you want

Fixing LAN:
---------------
I copy the instruction of @5T33Z0 's repo [Gigabyte-Z490-Vision-G-Hackintosh-OpenCore](https://github.com/5T33Z0/Gigabyte-Z490-Vision-G-Hackintosh-OpenCore). Please go to the repo and give this buddy a star 🌟.
Read the instruction [here](Fix_Ethernet.md)

Wifi Installation:
---------------
Go to this @chris1111 's [Wireless USB OC Big Sur Adapter](https://github.com/chris1111/Wireless-USB-OC-Big-Sur-Adapter) and get the installer file. SIP already disabled.


Fixing iServices:
--------------
Create a network Bridge from Ethernet & Wifi and enjoy 😁😁😁