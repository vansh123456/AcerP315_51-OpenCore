# Predator Helios 300 EFI PH315-51 (OC 0.6.7)

 ![configuration](https://i.ibb.co/bQBcphJ/Screenshot-2020-08-23-at-2-43-45-AM.png)

## Configuration
**CPU** : Intel Core i5-8300HH @ 2,3Ghz - 4,0Ghz

**GPU** : Intel UHD Graphics 630 

**RAM** : 08GB @ 2666Mhz

**STORAGE** : 400GB(Partitioned HDD) (for MacOS)

**OS** : MacOS Catalina (10.15.6)

## What's working

- [x] Battery percentage

- [x] Boot chime

- [x] Boot menu `OpenCanopy` 

- [x] CPU power management / performance `Now on par with Windows without XTU undervolt.`

- [x] GPU UHD 630 hardware acceleration / performance 

- [x] iMessage, FaceTime, App Store, iTunes Store. **Generate your own SMBIOS**

- [x] Qualcomm Atheros Realtek LT8211 PCI Express Gigabit Ethernet 

- [x] Keyboard `Volume and brightness hotkeys..`

- [x] Microphone `Working built-in`

- [x] Realtek® ALC255 Audio 'Layout-ID is choosen to be 3(you can also try 27)0 and another Program is installed for HeadPhone Jack to work Properly'

- [x]Here is the whole conversation taken from reddit.'Hello there, I'm sorry for the late repy but this is how I fix the audio distortion.
 1 Download or Clone the ComboJack repository from this link https://github.com/hackintosh-stuff/ComboJack
 2 put ComboJack_Installer/VerbStub.kext in OC/Kexts
 3 Make sure to add the kext into your config.plist (I used ProperTree because I only need to screenshot my OC folder using Ctrl+R or Command+R in Mac)
 4 Run ComboJack_Installer/install.sh in terminal and reboot
 5 Done. Whenever you attach a device through the jack there will be a popup (like this) asking about the device type.' 

- [x] USB-C

- [x] USB Ports `Works FINE`

- [x] Web camera 'Leaving FaceTime Works Everywhere'

- [x] Sleep/Wake 'Works FINE'

## Bios settings

- `Virtualization -> Intel Virtualization Technology` **Enabled**

- `Virtualization -> Intel VT-d Feature` **Should be Disabled**

- `Secure Boot -> Secure Boot` **Disabled**

- `FastBoot` **Disabled**

- `Sata Mode -> ACPI`
