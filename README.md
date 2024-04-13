# Hackintosh-Ryzen-3-1300x-RX-470

Used OpenCore Version 0.9.1 --
https://dortania.github.io/OpenCore-Install-Guide/ 

Last referenced video - https://youtu.be/DqrshDmNFu4?si=R60G7y69kduC-62G

# What is a Hackintosh?
A Hackintosh is a computer that runs Apple's Macintosh operating system macOS on computer hardware not authorized for the purpose by Apple.

# My Specifications (Running dual boot)
-Ryzen 3 1300x
-RX 470
-Asus Prime A320m-K
-8gb Hyper Fury 2133mhz
-OSCOO 128gb SSD (MacOS)
-WD green 500gb (Windows)
-WD Blue 1 TB (Windows)
-TP-Link UB400
(Using SMBIOS iMac 19,1) 

# FAQ
-Facetime,imessage and all the things are working fine.
-All icloud services are working.
-Audio also works fine
-Bluetooth working natively with TP-Link UB-400
-Airdrop,Handoff and other continuity feature are not working as of now as not using a apple supported wireless card yet though will update it soon.

# Specific Things Post install I Did.

set ALCID = 3 in bootargs --
Added few kexts for Bluetooth to work.

# About AMD non supported softwares
yes amd might struggle in virtualisation softwares as per the guide but i was working in android studio without using Android emolator (Virtualisation) it is working completely fine.

# Bios Changes
allowed the installation file referencing the youtube video which is as follows...
Bios Key Management section in this video very important - https://youtu.be/K9iyMm7PvYc?si=G29WfFnmfL34rciH

# Below are images of BIOS setting Recommended from the guide and ones which i changed back then which finally worked.

I don't exactly remember i turned fTPM enable or disable will update untill then try both if you can read this line.
I don't exactly remember i set OS Type to Windows UEFI or Other OS will update.

![WhatsApp Image 2024-04-14 at 04 58 14 (1)](https://github.com/kunwarx08/Hackintosh-Ryzen-3-1300x-RX-470/assets/128555024/3b77c1aa-7fdf-4764-81be-47c4a2fa6a38)
![WhatsApp Image 2024-04-14 at 04 58 14 (2)](https://github.com/kunwarx08/Hackintosh-Ryzen-3-1300x-RX-470/assets/128555024/abc92b48-327a-4fa1-a7df-d4cb4cc15da3)
![WhatsApp Image 2024-04-14 at 04 58 14 (3)](https://github.com/kunwarx08/Hackintosh-Ryzen-3-1300x-RX-470/assets/128555024/ad8a10e9-4d5f-4da4-86ef-e3aeacc85ade)
![WhatsApp Image 2024-04-14 at 04 58 14](https://github.com/kunwarx08/Hackintosh-Ryzen-3-1300x-RX-470/assets/128555024/316b3bf0-f4bc-41b7-af7e-f3739c8480c9)


