# DELL OptiPlex 3050 All-In-One OpenCore EFI (ONLY FOR VENTURA)
OpenCore EFI for Dell OptiPlex 3050 All-In-One


This EFI is OCSimplify builded and self-builded (some kexts/config strings i get from simplify build)

# Fast navigation
- [Hardware](#hardware)
- [Info](#info)
- [Another info](#another-info)
- [Working features list](#whats-working)
- [Bugs list](#bugs)  [Why these bugs isnt fixable?](#why-these-bugs-isnt-fixable)
- [DOWNLOAD EFI](#where-i-can-download-efi)

# Another links
- [EFI for macOS Sonoma](https://github.com/lowplgr/DellOP3050AIO-ocefi/blob/main/SonomaEFI.md)



# 
![Screenshot 2025-01-05 at 1 55 48 PM](https://github.com/user-attachments/assets/d003cb9b-416a-46f5-b4af-f100edbc03bd)

# Hardware
|           | Specs |
| --------- | ----- |
| CPU       | Intel Core i5-6400T Quad-core 2.2GHz (Sky Lake) |
| iGPU      | Intel HD Graphics 530 (Sky Lake) spoofed to HD Graphics 630 (Kaby Lake) |
| Chipset   | Intel B250 |
| RAM       | 4GB DDR4 SO-DIMM Non-ECC one-channel 2133MHz |
| Screen    | 19.5" TN WLED (1600x900@60Hz \| 16:9) |
| Storage   | TOSHIBA MQ01ACF050 500Gb HDD |
| Camera    | 1.0 MegaPixels 720P HD Integrated camera |
| Network (wireless) + Bluetooth | Intel 8265 802.11ac + Bluetooth 4.2 Card |
| Network (wired) | Realtek RTL8111HSD-CG Ethernet LAN 10/100/1000 |
| Audio     | Realtek ALC3661 |
| I/O Ports | 6 external USB ports: USB3.0 x4, USB2.0 x2 ; DisplayPort 1.2 ; VGA ; Audio Jack |


# Info
|         | Version |
| ------- | ------- |
| OpenCore | 1.0.2 |
| macOS   | Ventura (13.5) (22G74) |

# Another info
|        | Info |
| ------ | ---- |
| SMBIOS | iMac19,1 |
| EFI supporting | Only macOS Ventura (wifi will not working on another macOS's) |












# Whats working
- Wi-Fi
- Bluetooth
- Webcam 
- Microphone
- Sleep mode

# Bugs
- Sound
- Brighness
> [!WARNING]
> THIS ISNT FIXABLE!

# Why these bugs isnt fixable?
- **Because, AppleALC dont supporting ALC3661, but you can use your bluetooth headphones, its working as well**
- **Brighness will not work because iMacs dont have brighness changing feature, so you can use macOS only with max brighness**

# Where i can download EFI?
[Google Drive](https://drive.google.com/file/d/1Qm5sjW4J-ZBitujzjBC6MjAJiXDzXTsK/view?usp=share_link)



