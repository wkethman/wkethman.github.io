---
permalink: /projects/
title: "Projects"
classes: wide
gallery:
- url: /images/ryzentosh/1.jpg
  image_path: /images/ryzentosh/1.jpg
- url: /images/ryzentosh/2.jpg
  image_path: /images/ryzentosh/2.jpg
- url: /images/ryzentosh/3.jpg
  image_path: /images/ryzentosh/3.jpg
- url: /images/ryzentosh/4.jpg
  image_path: /images/ryzentosh/4.jpg
- url: /images/ryzentosh/5.jpg
  image_path: /images/ryzentosh/5.jpg
- url: /images/ryzentosh/6.jpg
  image_path: /images/ryzentosh/6.jpg
---

## Ryzentosh
Geekbench 5 Single-Core: 1138, Multi-Core: 10881
{% include figure image_path="/images/ryzentosh/ryzentosh.png" %}
### Hardware
{% include gallery %}
- Case: [*NZXT H1*](https://www.nzxt.com/products/h1-matte-white)
- Motherboard: [*ASUS ROG Strix B450-I mITX*](https://www.asus.com/us/Motherboards/ROG-STRIX-B450-I-GAMING/)
- CPU: Ryzen 9 3900X Matisse 3.8GHz 12-Core AM4
- Video card: [*AMD RX 5700XT*](https://www.powercolor.com/product?id=1565842787)
- Ram: Ripjaws V 32GB (2 x 16GB) DDR4-3200
- Hard drive: 1TB SSD 3D NAND M.2 2280 PCIe NVMe 3.0 x4 Solid State Drive
- Wireless/Bluetooth: BCM94352Z/DW1560

### Bios configuriaton
BIOS v3004 
*Boot*
- Fast Boot -> Disabled
- CSM -> Launch CSM -> Disabled
- Secure Boot -> OS Type -> Windows UEFI
*Advanced*
- USB Configuration -> XHCI Hand-off -> Enabled
- Core Performance Boost -> Disabled

### OpenCore Configuration
I followed the [AMD OS X Vanilla Guide](https://vanilla.amd-osx.com/) , went over to [dortania.github.io](https://dortania.github.io/OpenCore-Desktop-Guide/) to configure OpenCore, and followed the following [dual-boot](https://www.tonymacx86.com/threads/macos-win-dual-boot-at-same-disk-with-opencore.295892/) guide.

#### Required kext files
[*Download kext files*](/assets/files/kexts-06202020.zip)
- AirportBrcmFixup.kext
- AMDRyzenCPUPowerManagement.kext
- AppleALC.kext
- AppleMCEReporterDisabler.kext
- BrcmBluetoothInjector.kext
- BrcmFirmwareData.kext
- BrcmPatchRAM3.kext
- Lilu.kext
- SmallTreeIntel82576.kext
- SMCAMDProcessor.kext
- VirtualSMC.kext
- WhateverGreen.kext

### Setup
I referenced an [Optimum Tech](https://www.youtube.com/watch?v=hVs7i-wm5W0) build video for quickly installing the B450-I and hardware in the NZXT H1 case and the [Small Form Factory](https://www.youtube.com/watch?v=HUTHN8reR38) motherboard WiFi adapter upgrade video to install the BCM94352Z adapter. 

### Credit
- Maf3r0
- acidanthera
- Shaneee
- CorpNewt
- AlGrey
- Hackintosh Slav 
- And many others

## 3D Printing
<figure class="half">
	<img src="/images/3dprinter/1.jpg">
	<img src="/images/3dprinter/2.jpg">
</figure>
I am currently printing [PLA/+](https://amzn.to/2SISKKY), [PETG](https://amzn.to/3dtZ7Kq), and [ABS](https://amzn.to/2YKHkKS) with a modified [Ender 3 Pro](https://amzn.to/2SN6c0v) running [Marlin firmware](https://github.com/wkethman/Marlin) connected through [Raspberry Pi](https://amzn.to/2SHXQaj) running [OctiPrint](https://octoprint.org/download/).

### Purchased upgrades
- [SKR 1.4 turbo - TMC2209 Motor drivers](https://amzn.to/2xI1MAI)
- [All metal extruder feeder drive](https://amzn.to/2YPZlXQ)
- [BLTouch](https://amzn.to/2L6w57p)
- [Filament runout sensor](https://amzn.to/2yCenpC)
- [LM2596 buck converter](https://amzn.to/35DOTUY)
- [5015 24V Blower fan](https://amzn.to/2SIlVy4)

### 3D Printed upgrades
- [Hydra fan duct](https://www.thingiverse.com/thing:4062242)
- [Filament runout sensor mount](https://www.thingiverse.com/thing:4014649)

### Miscellaneous accessories
- [M2/3/4 steel screws, nuts, and washers](https://amzn.to/3b7e0Ra)
- [Raspberry Pi](https://amzn.to/2SHXQaj)

## Software development
<table>
	<tr>
		<td><img src="/images/development/trauma_guide_200.png" alt="Trauma Guide" width="70" height="70"></td>
		<td><h1>Trauma Guide</h1></td>
	</tr>
</table>
- Platform for providing up-to-date evidence-based protocols and educational materials to guide the care and scholarly pursuit of improved care for the traumatically injured
- Available on [iOS](https://itunes.apple.com/us/app/trauma-guide/id1462123331?mt=8&ign-mpt=uo%3D2) and [Android](https://play.google.com/store/apps/details?id=com.stanfordtrauma.guide)

<table>
	<tr>
		<td><img src="/images/development/expert_or_200.png" alt="Expert OR" width="70" height="70"></td>
		<td><h1>Expert OR</h1></td>
	</tr>
</table>
- Platform for sharing high-quality curated surgical and medical education videos
- Available on [Android](https://play.google.com/store/apps/details?id=com.wckethman.expertor&hl=en_US)

<table>
	<tr>
		<td><img src="/images/development/res_connect_200.png" alt="Resident Connect" width="70" height="70"></td>
		<td><h1>Resident Connect</h1></td>
	</tr>
</table>
- Collaborative hospital directory for healthcare professionals in use at [Stanford Healthcare](https://stanfordhealthcare.org/) and [University Hospitals](https://www.uhhospitals.org/)
- Available on [iOS](https://itunes.apple.com/us/app/resident-connect/id1367311896?mt=8) and [Android](https://play.google.com/store/apps/details?id=com.wckethman.rescon&hl=en_US) (Demo University – Passcode: demo)

<table>
	<tr>
		<td><img src="/images/development/tu.png" alt="TMedWeb" width="60"></td>
		<td><h1>TMedWeb</h1></td>
	</tr>
</table>
- Principal software developer of MedSource, a curriculum management system used at the Tulane University School of Medicine. MedSource is a subsidy of TMedWeb, an online learning community developed by a group of medical students committed to changing the paradigm of medical education and encouraging active collaboration between administrators, professors, and students.
- Available at [TMedWeb](http://tmedweb.tulane.edu/clubs/home/)