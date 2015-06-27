####OpenELEC unVM Beta####
Open Embedded Linux Entertainment Center (OpenELEC) is a small Linux distribution built from scratch as a platform to turn your computer into an XBMC media center.  An unVM is different from a traditional VM in its ability to have direct I/O interaction with underlying physical hardware such as PCI and USB devices (video/audio devices, mice, keyboards, or even a [Flirc](http://flirc.tv "Flirc")).  As an unVM, OpenELEC can now run on any unRAID 6 server that has capable hardware.  No "install" required, just download and run!  Now your unRAID server can also be your media player!

After starting your OpenELEC unVM, you can access your media by adding files, selecting SMB (or another protocol you have enabled), and then browsing to your system/share.  Enjoy!

####Host Requirements####
 - Processor / motherboard capable of Intel VT-d or AMD-Vi technology

 - PCIe GPU from either AMD or nVIDIA (others may work, but no support for on-board graphics)

 - Must be running unRAID 6 beta 10a or later

 - Must add pcie_acs_overide=downstream to append line in syslinux.cfg

####unVM Requirements####
 - 300MB of free disk space

 - 512MB of RAM

 - 1 vCPU
