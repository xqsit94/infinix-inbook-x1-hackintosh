<div align="center">
<h1>Infinix Inbook X1 (Ice Lake) Hackintosh</h1>
<h6>Education Purpose Only | Read <a href="#disclaimer">Disclaimer</a> Before You Proceed</h6>
<a href="https://github.com/xqsit94/gridsome-starter-geek-blog/blob/main/LICENSE"><img alt="GitHub" src="https://img.shields.io/github/license/xqsit94/infinix-inbook-x1-hackintosh?color=green&logo=github"></a>
<a href="https://github.com/xqsit94/infinix-inbook-x1-hackintosh/pulls"><img alt="PRs Welcome" src="https://img.shields.io/badge/PRs-welcome-brightgreen"></a>
</div>
<br>

## Configurations
| Specifications      | Detail                                      |
|---------------------|---------------------------------------------|
| Computer model      | Infinix Inbook X1 XL11                      |
| Processor           | Intel Core i3 1005G1 / Intel Core i5 1035G1 |
| Memory              | 8GB LPDDR4X                                 |
| Integrated Graphics | Intel UHD Graphics 630                      |


## OpenCore (Version: 0.7.5 - stable) + macOS Big Sur (Version 11.6+)
- https://dortania.github.io/OpenCore-Install-Guide/
- https://github.com/acidanthera/OpenCorePkg/releases/tag/0.7.5

## Supported Models
- Infinix Inbook X1 - i3 and i5 variant
- Infinix Inbook X1 - i7 variant ( ❌ Not Tested )

## BIOS Settings
#### 1. Disable
- Secure Boot (Default)
- Fast Boot
- VT-d

#### 2. To fix cursor glitch
```
Goto Bios Settings -> Chipset Section -> System Agent (SA) Configuration -> Graphics Configuration

Set DVMT Total Gfx Memory setting to Max
Set DVMT PPre-Allocated Setting to 160M
```


## What Works?
- Wifi
- Mic
- Keyboard
- Trackpad
- Backlight
- Brightness
- Battery Indication
- etc

## What not Works?
- Bluetooth
- HDMI port
- Sleep
- etc (test and let me know)

## Pull Request
- PRs are welcomed and appreciated for fixing bugs/issues

## Full Credits
- [Awans ID](https://www.instagram.com/awans.id/)
- [Zidan](https://www.instagram.com/zidan1909/)
- OC and Kexts devs

Thanks for making this efi possible.

## Disclaimer
Your warranty may be void. Please do some research if you have any concerns before replacing your EFI with mine. I am not responsible for any loss, including but not limited to Kernel Panic, device fail to boot or can not function normally, storage damage or data loss, atomic bombing, World War III, The CK-Class Restructuring Scenario that SCP Foundation can not prevent, and so on.