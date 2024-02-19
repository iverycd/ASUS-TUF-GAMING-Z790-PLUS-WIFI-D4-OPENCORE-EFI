# ASUS-TUF-GAMING-Z790-PLUS-WIFI-D4-OPENCORE-EFI

## HARDWARE


| Hardware    | Description                             | Work or not |
| ----------- | --------------------------------------- | ----------- |
| CPU         | 13th Gen Intel(R) Core(TM) i7-13700KF   | ✅           |
| Motherboard | ASUS TUF GAMING Z790-PLUS WIFI D4      | ✅           |
| GPU         | Sapphire RX 6600XT 8G        | ✅           |
| RAM         | G.Skill Trident Z Royal 3600MHz 16GB*2 F4-3600C18D-32GTRG| ✅           |
| RAM         | CORSAIR 3600MHz 32G*1 CM4X32GC3600C18K2D-CN Ver 3.44| ✅           |
| SSD         | SN850X 2T PCIE4.0  | ✅           |
| Sound Card  | Realtek-S1220A                          | ✅           |
| Ethernet    | Intel I226-V 2.5Gb              | ✅           |
| WNIC        | Intel Wi-Fi 6 AX201 With BT 5.2         | ✅           |



## DOWNLOAD MACOS

From a macOS machine that meets the requirements of the OS version you want to install, go directly to the App Store and download the desired OS release and continue to Setting up the installer.


## Setting up the installer
Formatting the USB to prep for both the macOS installer and OpenCore

![image](https://github.com/iverycd/ASUS-TUF-GAMING-Z790-PLUS-WIFI-D4-OPENCORE-EFI/assets/35289289/8412a816-800a-4548-873a-9ccd003018b7)


Next run the createinstallmedia command provided by Apple. Note that the command is made for USB's formatted with the name macinstall:

```bash
sudo /Applications/Install\ macOS\ Sonoma.app/Contents/Resources/createinstallmedia --volume /Volumes/macinstall
```

![image](https://github.com/iverycd/ASUS-TUF-GAMING-Z790-PLUS-WIFI-D4-OPENCORE-EFI/assets/35289289/47d63f52-3c1f-4437-97d4-eaea42b8dc0c)


## Setting up OpenCore's EFI environment

Use MountEFI for mount
https://github.com/corpnewt/MountEFI

Mount your usb disk and copy opencore EFI directory to target like below

![image](https://github.com/iverycd/ASUS-TUF-GAMING-Z790-PLUS-WIFI-D4-OPENCORE-EFI/assets/35289289/1096ac45-5fe8-4917-8b70-05aa21866507)




## Bios adjust

- disable fast boot

- disable CSM

- disable Serial Port





## Boot from usb device
install macOS
![image](https://github.com/iverycd/ASUS-TUF-GAMING-Z790-PLUS-WIFI-D4-OPENCORE-EFI/assets/35289289/af52e197-41b6-4283-9a9b-4b88043aa6b5)


![image](https://github.com/iverycd/ASUS-TUF-GAMING-Z790-PLUS-WIFI-D4-OPENCORE-EFI/assets/35289289/fd366548-a48f-4980-90b4-134b605f333e)


![image](https://github.com/iverycd/ASUS-TUF-GAMING-Z790-PLUS-WIFI-D4-OPENCORE-EFI/assets/35289289/c1234e5e-17bc-4f4f-82fd-eee22a0718d6)


![image](https://github.com/iverycd/ASUS-TUF-GAMING-Z790-PLUS-WIFI-D4-OPENCORE-EFI/assets/35289289/a1151e19-354c-4245-bcdc-65be1ceaa739)

![image](https://github.com/iverycd/ASUS-TUF-GAMING-Z790-PLUS-WIFI-D4-OPENCORE-EFI/assets/35289289/f0761ede-da54-42b5-a9f6-adab6241984b)


![image](https://github.com/iverycd/ASUS-TUF-GAMING-Z790-PLUS-WIFI-D4-OPENCORE-EFI/assets/35289289/54d2dc66-ebc7-457e-a861-2c92fad7a787)



