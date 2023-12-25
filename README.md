# MSI Z87-GD65 GAMING

OpenCore EFI for MSI Z87-GD65 GAMING

![about](https://raw.githubusercontent.com/randvmbone/MSI-Z87-GD65-GAMING/main/about.png)

### Hardware

* **MOBO:** MSI Z87-GD65 GAMING
* **CPU:** Intel Core i5-4690K
* **RAM:** G.Skill DDR3-2400 16GB (2x8GB)
* **GPU:** MSI Radeon RX 480 GAMING X 8G
* **SSD:** Crucial MX500 500GB

### BIOS Settings

* Settings
	* Advanced
		*  Super IO Configuration
			*  Serial(COM) Port0 → **Disabled**
		*  Windows 8/8.1 Configuration
		   *  Fast Boot → **Disabled**
* Overclocking
	* CPU Features
	  * Intel VT-D Tech → **Disabled**
	  * CFG Lock → **Disabled**

### macOS Support
| Version   | macOS | Download |
| --------: | :---- | :------- |
| 14.2 | Sonoma | [Mac App Store](https://apps.apple.com/app/macos-sonoma/id6450717509?mt=12) |
| 13.6 | Ventura | [Mac App Store](https://apps.apple.com/app/macos-ventura/id1638787999?mt=12) |
| 12.7 | Monterey | [Mac App Store](https://apps.apple.com/app/macos-monterey/id1576738294?mt=12) |
| 11.7.10 | Big Sur | [Mac App Store](https://apps.apple.com/app/macos-big-sur/id1526878132?mt=12) |
| 10.15.7 | Catalina | [Mac App Store](https://apps.apple.com/app/macos-catalina/id1466841314?mt=12) |
| 10.14.6 | Mojave | [Mac App Store](https://apps.apple.com/app/macos-mojave/id1398502828?mt=12) |
| 10.13.6 | High Sierra | [Mac App Store](https://apps.apple.com/app/macos-high-sierra/id1246284741?mt=12) |

### Sonoma

* OCLP
	* ```boot-args: amfi=0x80 ipc_control_port_options=0```
