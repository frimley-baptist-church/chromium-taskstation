## Installation procedure

**Download Ubuntu Server 20.04**

* Download this file to your machine https://releases.ubuntu.com/20.04.3/ubuntu-20.04.3-live-server-amd64.iso
* Grab an 4GB or larger USB storage device and use https://www.balena.io/etcher/ to install the `.iso` file on the storage device. **Warning: You will loose any files on the storage device!**

**Install Ubuntu Server on the PC**

* Connect the PC to a working Ethernet port.
* Place the USB device in the machine, power up and choose to boot from the USB device labelled Ubuntu Server 20.04.3 and proceed to install Ubuntu. It will take a while so be patient. If you're not familiar with installing Ubuntu Linux, please consult the internet.

**Install the Chromium Taskstation application**

* Login to the unit, which should remain connected to the internet, and execute the following:
```
$ sudo -i
# apt update
# apt dist-upgrade
# apt install wget
# wget https://frimley-baptist-church.github.io/chromium-taskstation/chromium-taskstation-1.0.deb
# dpkg -i chromium-taskstation-1.0.deb
```

During the installation you will be asked for web page address that you want your taskstation/kiosk to use as it's home page.

After the installation and configuration are complete, if all is well, the PC should be ready for action. At this point you can hit the power button on the machine to shut the computer off. This usually takes 10 seconds or so, with lots of scrolling text to watch as it performs this action.

**Testing the setup**

* Hit the power button, sit back and watch.
* You should eventually see your chosen home page.
