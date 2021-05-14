Intro
---

This Repo has my OpenCore EFI folder for anyone trying to run macOS 11.X+ on their Dell Latitude E5430 (non-vPro)
#### My legacy Clover macOS 10.15+ folder is also avaiable but deprecated and no longer supported
Specs:

__**Dell Latitude E5430 (Non-vPro)**__
- **CPU** : Intel Core i7-3630QM 4C8T 2.4GHz (3.4GHz turbo)
- **RAM** : 12GB dual-channel 1600MHz DDR3
- **GPU** : Intel HD Graphics 4000
- **Storage** : ADATA 120GB SSD
- **Screen** : 14.9" 1600x900
- **WiFi** : DW1510 (needs patching)
- **Soundcard** : IDT 92HD93
- **Battery** : 60 WHr

Hardware compatibility
---

TL;DR - 

**What works:**

- CPU power management
- Readng CPU temperature
- GPU acceleration and video codecs
- SATA SSD
- Wireless **[after being replaced]**
- Sleep (Trackpad and Keyboard unresponsive after wakeup, needs work)
- Trackpad including gestures
- All USB ports
- Screen full resolution, brightness
- HDMI
- iMessage and iCloud
- AirPlay

**What does not work/disabled:**
- Internal webcam with Facetime (No Webcam hardware)
- Battery Capacity (At least on Big Sur)
- Audio (At least on Big Sur)
- Bluetooth

**Not tested:**
