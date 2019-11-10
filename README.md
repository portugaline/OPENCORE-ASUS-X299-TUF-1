# OPENCORE-ASUS-X299-TUF-1
Opencore / Asus x299 TUF MARK 1


Working with Catalina 10.15.1



NOTES:

<b>USBMap.kext</b>
* Add your "Board Serial Number"/"System Serial Number"/"SystemUUID" in:
- plataforminfo/SMBIOS

* Add your "System Serial Number"/"SystemUUID" in:
- plataforminfo/Generic

* Add your "System Serial Number"/"SystemUUID" in:
- plataforminfo/DataHub

<b>USBMap.kext</b>
* 4 USB2 in backpainel set to USB2
* 4 USB3 in backpainel set to USB2and3
* 2 USB3 ports in front (1 SET TO USB2 bacause i have my bluetooth usb there, the other USB2and3)

<b>AGPMInjector.kext</b>
* SET to ImacPro1,1 and RX580
* Please do your own using: https://github.com/Pavo-IM/AGPMInjector

<b>TSCAdjustReset.kext</b>
* The TSCAdjustReset.kext is set for i9 7900x, please edit if you have a different CPU

# Hardware used in my build

<b>Hardware:</br>
* Intel i9 7900X
* Asus X299 TUF Mark 1
* Gigabyte RX580 8GB
* Samsung SSD 970 EVO 250GB
* 32GB 2666Mhz (4x8GB)
* BCM920702 Bluetooth 4.0

<b>Main important BIOS settings:</b>
* Asus Multicore: Auto
* CPU Core Ratio: All Core Sync
* MSR Lock: Disabled
* Legacy USB: Disabled
* Above 4G ecoding: Enabled
* CSM: Disabled
* OS Type: Windows UEFI
