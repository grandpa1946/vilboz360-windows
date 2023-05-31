# Windows 10 on the Lenovo Chromebook 300e (3rd gen)
Probably works on other Zork AMD 3015ce chromebooks.
# ONLY WORKS ON EXTERNAL USB DRIVES, EXTERNAL SSD'S...
# How to install?
* Enable dev mode (duh)
* Run [MrChromebox's firmware utility](https://mrchromebox.tech/#fwscript) and install the legacy firmware
* Create a 1gb FAT32 partition on the usb drive and paste in the efi folder.
* Plug in the target usb and the Windows 10 installer
* Boot into the uefi firmware and press escape and boot into **the target usb with the efi partition**
* You will boot into opencore, select the windows installer.
* Install Windows normally
* Boot into windows and install all the drivers
# How to get graphics drivers?
* Goto device manager
* Click on **Display adapters**
* Right click **Microsoft basic display adapter**
* Select **update driver**
* Click **Let me pick from a list**
* Click **Have disk**
* Open the graphics driver directory and select the inf file that begins with "C"
* Deselect "show compatible hardware"

# Credits to [CoolStar](https://coolstar.org/) for all the drivers and the Efi creator script
