# VanillaHackintosh
For educational purpose

<B>EFI Folder</B>
- Asus ROG Maximus XI Hero (WiFi) (BIOS ver: 0602)
- i7-8700k

For High Sierra 10.13.6 (17G6030)
Note that earlier minor versions of 10.13.6 has "Graphics Driver failed to load. Could not register with Framebuffer driver" issue with iGPU (UHD 630).

<B> Discovery </B>
- EmuVariableUefi-64.efi 
-- is required for your FaceTime or iMessage to work
- ApfsDriverLoader-64.efi
-- is required if you are going for Mojave or APFS (10.13.6)

<B> Working </b>
- Sleep, Wake, Restart, Shutdown
- Audio
- USB

<B> Steps </B>
1. Create a High Sierra USB 
2. Install Clover on USB
3. Copy EFI folder over the one in USB
4. Boot your PC up with the USB stick.
5. Install your High Sierra on SSD.
