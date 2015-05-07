# Emulating Raspbian on Windows

<img src="http://www.googledrive.com/host/0B9NJr90onOFaM3FURm5BLUZJdkU" width="240px" />

### Getting Started
The first thing we'll need to do is get a copy of our QEMU machine emulator to run our ARM image, the Raspbian image itself, and a copy of the Linux kernel specifically tailored for the Pi's hardware:

1. Download the [latest version](http://qemu.weilnetz.de/w32/qemu-w32-setup-20150503.exe) of *QEMU for Windows* and install it
2. Create a local directory to hold the Raspbian image and Pi kernel
3.  Download a tweaked version of the [Raspbian image](https://docs.google.com/uc?id=0B9NJr90onOFaNm1ZYmVDLVluX0U&export=download) to your local folder and extract the image from the zip file *(Right-click, Extract All...)*
4. Download a copy of the [Raspberry Pi kernel](http://xecdesign.com/downloads/linux-qemu/kernel-qemu) to your local folder

### Running QEMU
