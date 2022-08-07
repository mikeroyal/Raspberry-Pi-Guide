<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/103486513-4cecbc80-4db3-11eb-89a0-fa155cbcdbda.png">
  <br />
  Raspberry Pi Guide
</h1>

#### A guide covering Raspberry Pi devices such as the Raspberry Pi 4 Model B and Raspberry Pi 400. Along with a wide variety of operating systems that you can install on your Raspberry Pi device. Also, learn about cool projects that you can build with your Raspberry Pi device.


**Note: You can easily convert this markdown file to a PDF in [VSCode](https://code.visualstudio.com/) using this handy extension [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf).**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/121087087-d5272180-c798-11eb-8c9a-16c32d2c7454.png">
</p>

# Table of Contents

1. [Models of Raspberry Pi boards](https://github.com/mikeroyal/raspberry-pi-Guide#models-of-raspberry-pi-boards)

2. [Raspberry Pi Learning Resources](https://github.com/mikeroyal/raspberry-pi-Guide#raspberry-pi-learning-resources)
    - [Books](#books)
    - [Podcasts](#podcasts)
    - [YouTube Channels](#youtube-channels)

3. [Raspberry Pi Operating Systems](https://github.com/mikeroyal/raspberry-pi-Guide#raspberry-pi-operating-systems)

4. [Raspberry Pi Tools](https://github.com/mikeroyal/raspberry-pi-Guide#raspberry-pi-tools)
     - [File systems](#file-systems)
     - [Tools for Home Automation](#Tools-for-Home-Automation)
     - [Getting Started with Home Assistant(HA)](#Home-Assistant)
     - [Getting Started with Homebridge](#Homebridge)
     - [Getting Started with ESPHome](#ESPHome)
     - [Turning Raspberry Pi into a Router](https://github.com/mikeroyal/raspberry-pi-Guide#Turning-Raspberry-Pi-into-a-Router)
     - [Setting up Watchdog Time (WDT) on Raspberry Pi](https://github.com/mikeroyal/Raspberry-Pi-Guide#setting-watchdog-timer-wdt-on-raspberry-pi)

5. [Raspberry Pi Upgrades](https://github.com/mikeroyal/Raspberry-Pi-Guide#raspberry-pi-upgrades)

6. [Getting Software](https://github.com/mikeroyal/Raspberry-Pi-Guide#getting-software)

7. [Using Android Apps on Raspberry Pi](https://github.com/mikeroyal/Raspberry-Pi-Guide#using-android-apps-on-raspberry-pi)

8. [Gaming](https://github.com/mikeroyal/Raspberry-Pi-Guide#gaming)
     - [Steam](https://github.com/mikeroyal/Raspberry-Pi-Guide#steam)
     - [ProtonDB](https://github.com/mikeroyal/Raspberry-Pi-Guide#protondb)
     - [Lutris](https://github.com/mikeroyal/Raspberry-Pi-Guide#lutris)
     - [GameHub](https://github.com/mikeroyal/Raspberry-Pi-Guide#gamehub)
     - [Heroic Game Launcher](https://github.com/mikeroyal/Raspberry-Pi-Guide#heroic-games-launcher)
     - [Game Streaming](https://github.com/mikeroyal/Raspberry-Pi-Guide#game-streaming)
     - [Game Emulators](https://github.com/mikeroyal/Raspberry-Pi-Guide#game-emulators)

9. [Home Media Server](https://github.com/mikeroyal/Raspberry-Pi-Guide#home-media-server)

10. [WireGuard](https://github.com/mikeroyal/Raspberry-Pi-Guide#wireguard)

11. [Nextcloud](https://github.com/mikeroyal/Raspberry-Pi-Guide#nextcloud)

12. [Grafana](https://github.com/mikeroyal/Raspberry-Pi-Guide#Grafana)

13. [Kubernetes](https://github.com/mikeroyal/Raspberry-Pi-Guide#kubernetes)

14. [Machine Learning](https://github.com/mikeroyal/Raspberry-Pi-Guide#machine-learning)

15. [Robotics](https://github.com/mikeroyal/Raspberry-Pi-Guide#robotics)

16. [Node.js Development](https://github.com/mikeroyal/Raspberry-Pi-Guide#nodejs-development)

17. [Java Development](https://github.com/mikeroyal/Raspberry-Pi-Guide#java-development)

18. [Python Development](https://github.com/mikeroyal/Raspberry-Pi-Guide#python-development)

19. [Rust Development](https://github.com/mikeroyal/Raspberry-Pi-Guide#rust-development)

20. [TypeScript Development](https://github.com/mikeroyal/Raspberry-Pi-Guide#typescript-development)
 
21. [HMTL/CSS Development](https://github.com/mikeroyal/Raspberry-Pi-Guide#hmtlcss-development)

22. [Ruby Development](https://github.com/mikeroyal/Raspberry-Pi-Guide#ruby-development)

23. [PHP Development](https://github.com/mikeroyal/Raspberry-Pi-Guide#php-development) 


# Models of Raspberry Pi boards

[Back to the Top](https://github.com/mikeroyal/raspberry-pi-Guide/blob/main/README.md#table-of-contents)

**Raspberry Pi 4 Model B**

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/103486342-08acec80-4db2-11eb-8696-f51475c9787a.jpeg">
</p>

[Check out the Raspberry Pi 4](https://www.raspberrypi.org/products/raspberry-pi-4-model-b/)

**Raspberry Pi 4 Model B Hardware Specifications**

 - Broadcom BCM2711, Quad core Cortex-A72 (ARM v8) 64-bit SoC @ 1.5GHz
 - 2GB, 4GB or 8GB LPDDR4-3200 SDRAM (depending on model)
 - 2.4 GHz and 5.0 GHz IEEE 802.11ac wireless 
 - Bluetooth 5.0, BLE
 - Gigabit Ethernet
 - 2 USB 3.0 ports; 2 USB 2.0 ports.
 - Raspberry Pi standard 40 pin GPIO header (fully backwards compatible with previous Pi boards)
 - 2 × micro-HDMI ports (up to 4kp60 supported)
 - OpenGL ES 3.0 graphics

**Raspberry Pi 400 Personal Computer Kit**

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/103486343-09458300-4db2-11eb-989a-6f0cd451c7b0.png">
</p>

[Check out the Raspberry Pi 400 Personal Computer Kit](https://www.raspberrypi.org/products/raspberry-pi-400/)

**Raspberry Pi 400 Hardware Specifications**

 - Broadcom BCM2711, Quad core Cortex-A72 (ARM v8) 64-bit SoC @ 1.8GHz
 - 4GB LPDDR4-3200 SDRAM 
 - 2.4 GHz and 5.0 GHz IEEE 802.11ac wireless 
 - Bluetooth 5.0, BLE
 - Gigabit Ethernet
 - 2 USB 3.0 ports; 2 USB 2.0 ports.
 - Raspberry Pi standard 40 pin GPIO header 
 - 2 × micro-HDMI ports (up to 4kp60 supported)
 - OpenGL ES 3.0 graphics
 
 **Raspberry Pi Zero 2 W**
 
[Raspberry Pi Zero 2 W](https://www.raspberrypi.com/products/raspberry-pi-zero-2-w/) is RP3A0, a custom-built system-in-package designed by Raspberry Pi in the UK. With a quad-core 64-bit ARM Cortex-A53 processor clocked at 1GHz and 512MB of SDRAM, Zero 2 is up to five times as fast as the original Raspberry Pi Zero.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/177431003-b8516786-97b6-4678-90e3-51e25c904b1e.png">
</p>

[Check out the Raspberry Pi Zero 2 W](https://www.raspberrypi.org/products/raspberry-pi-zero-2-w/)

**Raspberry Pi Zero 2 W Hardware Specifications:**

- 1GHz quad-core 64-bit Arm Cortex-A53 CPU
- 512MB SDRAM
- 2.4GHz 802.11 b/g/n wireless LAN
- Bluetooth 4.2, Bluetooth Low Energy (BLE), onboard antenna
- Mini HDMI port and micro USB On-The-Go (OTG) port
- microSD card slot
- CSI-2 camera connector
- HAT-compatible 40-pin header footprint (unpopulated)
- H.264, MPEG-4 decode (1080p30); H.264 encode (1080p30)
- OpenGL ES 1.1, 2.0 graphics
- Micro USB power
 
 **Raspberry Pi Pico Microcontroller**
 
<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/105645203-e6593c80-5e4e-11eb-96cb-66f64a9a4367.png">
</p>

[Check out the Raspberry Pi Pico](https://www.raspberrypi.org/products/raspberry-pi-pico/)

**Raspberry Pi Pico Hardware Specifications**

 - RP2040 microcontroller chip designed by Raspberry Pi in the UK
 - Dual-core Arm Cortex-M0+ processor, flexible clock running up to 133 MHz
 - 264KB on-chip SRAM
 - 2MB on-board QSPI Flash
 - 26 multifunction GPIO pins, including 3 analogue inputs
 - 2 × UART, 2 × SPI controllers, 2 × I2C controllers, 16 × PWM channels
 - 1 × USB 1.1 controller and PHY, with host and device support
 - 8 × Programmable I/O (PIO) state machines for custom peripheral support
 - Castellated module allows soldering direct to carrier boards
 - Drag-and-drop programming using mass storage over USB
 - Low-power sleep and dormant modes
 - Accurate on-chip clock
 - Temperature sensor
 - Accelerated integer and floating-point libraries on-chip
 
**Raspberry Pi Pico W**

[Raspberry Pi Pico W](https://www.raspberrypi.com/news/raspberry-pi-pico-w-your-6-iot-platform/) is just like the classic Pico but adds on-board single-band 2.4GHz wireless interfaces (802.11n) using the Infineon CYW4343 while retaining the Pico form factor. 

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/177430870-9737b7fa-688b-485b-8057-000e57618de1.png">
</p>

[Checkout the Raspberry Pi Pico W](https://www.raspberrypi.com/products/raspberry-pi-pico/)

**Raspberry Pi Pico W Hardware Specifications:**

- Dual-core Arm Cortex-M0+ processor, flexible clock running up to 133 MHz
 - 264kB on-chip SRAM
 - 2 × UART, 2 × SPI controllers, 2 × I2C controllers, 16 × PWM channels
 - 1 × USB 1.1 controller and PHY, with host and device support
 - 8 × Programmable I/O (PIO) state machines for custom peripheral support
 - Supported input power 1.8–5.5V DC
 - Operating temperature -40°C to +85°C
 - Drag-and-drop programming using mass storage over USB
 - Low-power sleep and dormant modes
 - Accurate on-chip clock
 - Temperature sensor
 
**Raspberry Pi Pico W**

[Raspberry Pi Pico H](https://www.raspberrypi.com/news/raspberry-pi-pico-w-your-6-iot-platform/) is just like the classic Pico but now comes with pre-soldered headers. A [3-pin JTAG connector](https://datasheets.raspberrypi.com/debug/debug-connector-specification.pdf) is now pre-soldered for debugging. 

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/177430872-c260a57e-99f2-43e9-8bfa-f4f772099909.png">
</p>

[Checkout the Raspberry Pi Pico H](https://www.raspberrypi.com/products/raspberry-pi-pico/)

**Raspberry Pi Pico H Hardware Specifications:**

 - Dual-core Arm Cortex-M0+ processor, flexible clock running up to 133 MHz
 - 264kB on-chip SRAM
 - 2 × UART, 2 × SPI controllers, 2 × I2C controllers, 16 × PWM channels
 - 1 × USB 1.1 controller and PHY, with host and device support
 - 8 × Programmable I/O (PIO) state machines for custom peripheral support
 - Supported input power 1.8–5.5V DC
 - Operating temperature -40°C to +85°C
 - Drag-and-drop programming using mass storage over USB
 - Low-power sleep and dormant modes
 - Accurate on-chip clock
 - Temperature sensor

**Raspberry Pi RP2040**

[RP2040](https://www.raspberrypi.com/products/rp2040/) is a microcontroller chip designed by Raspberry Pi.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/177430875-51c05f65-6cac-4624-8c4d-e6ff7979c41d.png">
</p>

[Checkout the Raspberry RP2040](https://www.raspberrypi.com/products/raspberry-pi-pico/)

**Raspberry Pi RP2040 Hardware Specifications:**

 - Dual-core Arm Cortex-M0+ processor, flexible clock running up to 133 MHz
 - 264kB on-chip SRAM
 - 2 × UART, 2 × SPI controllers, 2 × I2C controllers, 16 × PWM channels
 - 1 × USB 1.1 controller and PHY, with host and device support
 - 8 × Programmable I/O (PIO) state machines for custom peripheral support
 - Supported input power 1.8–5.5V DC
 - Operating temperature -40°C to +85°C
 - Drag-and-drop programming using mass storage over USB
 - Low-power sleep and dormant modes
 - Accurate on-chip clock
 - Temperature sensor

**Raspberry Pi OS. The default Operating System for every Raspberry Pi device**

[Check out Raspberry Pi OS](https://www.raspberrypi.org/software/operating-systems/)

<img src="https://user-images.githubusercontent.com/45159366/103486345-0a76b000-4db2-11eb-9e96-e7f234bdc950.png">


# Raspberry Pi Learning Resources

[Back to the Top](https://github.com/mikeroyal/raspberry-pi-Guide/blob/main/README.md#table-of-contents)

[Raspberry Pi](https://www.raspberrypi.org/) is an ARM powered single board computer(SBC) that is the size of a credit card and costs around $35.

[Raspberry Pi Foundation](https://www.raspberrypi.org/about/) is a UK-based charity that works to put the power of computing and digital making into the hands of people all over the world.

[Getting Started with Raspberry Pi Projects](https://projects.raspberrypi.org/)

[Online learning for the Raspberry Pi](https://www.raspberrypi.org/training/online/)

[Raspberry Pi Training Program](https://www.raspberrypi.org/training/)

[Raspberry Pi Online Courses on Udemy](https://www.udemy.com/topic/raspberry-pi/)

[Raspberry Pi Online Courses on Coursera](https://www.coursera.org/courses?languages=en&query=raspberry%20pi)

[The Raspberry Pi Platform and Python Programming course on Coursera](https://www.coursera.org/learn/raspberry-pi-platform)

[Learning Raspberry Pi with Online Courses on edX](https://www.edx.org/learn/raspberry-pi)

[Raspberry Pi Online Training Courses on LinkedIn Learning](https://www.linkedin.com/learning/topics/raspberry-pi)

[Getting Started with Raspberry Pi course on FutureLearn](https://www.futurelearn.com/courses/getting-started-with-your-raspberry-pi)

[Home Assistant on Raspberry Pi](https://www.home-assistant.io/getting-started/)

[PiSwitch: Build your own Nintendo Switch-style console](https://magpi.raspberrypi.org/articles/piswitch-nintendo-switch-console)

[How to set Watchdog Timer on Raspberry Pi | IoT Assistant](https://iotassistant.io/raspberry-pi/how-to-set-watchdog-timer-raspberrypi/)

[Writing to file on RAM Disk on Raspberry Pi | IoT Assistant](https://iotassistant.io/raspberry-pi/writing-to-file-on-ram-disk-on-raspberry-pi/)

### Books

- [The Official Raspberry Pi Handbook (2022)](https://magpi.raspberrypi.com/books/handbook-2022)  

- [The Official Raspberry Pi Handbook (2021)](https://magpi.raspberrypi.com/books/handbook-2021) 

- [Raspberry Pi Beginner's Book 1](https://magpi.raspberrypi.com/books/beginners-1) 

- [Raspberry Pi Beginner's Guide for **Raspberry Pi 3B+**](https://magpi.raspberrypi.com/books/beginners-guide) 

- [Raspberry Pi Beginner's Guide v2 for **Raspberry Pi 4**](https://magpi.raspberrypi.com/books/beginners-guide-2nd-ed) - 

- [Raspberry Pi Beginner's Guide v3 for **Raspberry Pi 4**](https://magpi.raspberrypi.com/books/beginners-guide-3rd-ed) 

- [Raspberry Pi Beginner's Guide v4 for **Raspberry Pi 4 and Raspberry Pi 400**](https://magpi.raspberrypi.com/books/beginners-guide-4th-ed)  

- [Raspberry Pi Projects Book v1](https://magpi.raspberrypi.com/books/projects-1) 

- [Raspberry Pi Projects Book v2](https://magpi.raspberrypi.com/books/projects-2) 

- [Raspberry Pi Projects Book v3](https://magpi.raspberrypi.com/books/projects-3) 

- [Raspberry Pi Projects Book v4](https://magpi.raspberrypi.com/books/projects-4) 

- [Raspberry Pi Projects Book v5](https://magpi.raspberrypi.com/books/projects-5) 

- [Retro Gaming with Raspberry Pi](https://magpi.raspberrypi.com/books/retro-gaming) 

- [Raspberry Pi Camera Guide](https://magpi.raspberrypi.com/books/camera-guide)

- [Raspberry Pi Essentials - GPIO Zero Electronics](https://magpi.raspberrypi.com/books/essentials-gpio-zero-v1) 

- [Raspberry Pi Essentials - Learn to Code with Scratch](https://magpi.raspberrypi.com/books/essentials-scratch-v1) 

- [Raspberry Pi Essentials - Make Games with Python](https://magpi.raspberrypi.com/books/essentials-games-vol1) 

- [Raspberry Pi Essentials - Learn to Code with C](https://magpi.raspberrypi.com/books/essentials-c-v1)  

- [Raspberry Pi Essentials - Making with Minecraft](https://magpi.raspberrypi.com/books/essentials-minecraft-v1)

### Podcasts
[Back to the Top](#table-of-contents)

  - [HomeTech](https://www.hometech.fm/about)
 
  - [Home Assistant](https://hasspodcast.io/episodes/)
 
  - [HomeKit Insider](https://www.listennotes.com/podcasts/homekit-insider-appleinsider-y-ZPnq5l1B_/)
  
  - [Home Tech Talk](https://www.hometechtalk.com.au/)
  
  - [Self-Hosted Podcast](https://selfhosted.show/) 
  
  - [Self-Hosted SRE(Site Reality Engineer) Podcast](https://sshsre.fireside.fm/)
  
  - [The Digital Lifestyle Show](https://podcasts.apple.com/us/podcast/the-digital-lifestyle-show/id217932939)
  
  - [Linux Weekly Daily Wednesday](https://podcasts.apple.com/us/podcast/linux-weekly-daily-wednesday/id1316136728)
  
  - [SBCGaming Podcast](https://podcasts.apple.com/us/podcast/sbcgaming-podcast/id1531624751)
  
  - [Adafruit Industries Podcast](https://podcasts.apple.com/us/podcast/adafruit-industries/id1086346278)

### YouTube Channels
[Back to the Top](#table-of-contents)

  - [Raspberry Pi](https://www.youtube.com/c/raspberrypi)

  - [Jeff Geerling](https://www.youtube.com/c/JeffGeerling)
  
  - [Level1Techs](https://www.youtube.com/c/Level1Techs)
 
  - [Open Source is Awesome](https://www.youtube.com/c/AwesomeOpenSource)
  
  - [Self-Hosted Show by Jupiter Broadcasting](https://www.youtube.com/watch?v=XBhhVHVQ148&list=PLUW3LUwQvegxit4XMxUNW3qrRFmgP_aaT)
 
  - [Techno Tim](https://www.youtube.com/c/TechnoTimLive)
 
  - [Raid Owl](https://www.youtube.com/c/RaidOwl)
  
  - [NextCloud](https://www.youtube.com/c/Nextcloud)
  
  - [Wolfgang's Channel](https://www.youtube.com/c/WolfgangsChannel)
  
  - [Pro Tech Show](https://www.youtube.com/c/ProTechShow)
  
  - [Geeked](https://www.youtube.com/c/GeekedTV)
  
  - [The Tinker Dad](https://www.youtube.com/c/TheTinkerDad)
  
  - [DB Tech](https://www.youtube.com/c/DBTechYT)
  
  - [The Digital Life](https://www.youtube.com/c/TheDigitalLifeTech)
 
  - [censiCLICK](https://www.youtube.com/c/censiCLICK)
  
  - [Home Network Geek](https://www.youtube.com/channel/UCCniXOLmZ85FHN8c8K_c0LA/featured)


# Raspberry Pi Operating Systems

[Back to the Top](https://github.com/mikeroyal/raspberry-pi-Guide/blob/main/README.md#table-of-contents)

[Raspberry Pi OS](https://www.raspberrypi.org/software/operating-systems/)

[Hass.io(Home Assistant OS)](https://www.home-assistant.io/hassio/installation/)

[Umbrel](https://umbrel.com/) 

[OmniROM(Android 11) based on ASOP](https://forum.xda-developers.com/t/omnirom-android-r-11-for-pi-4.4183121/)

[Manjaro Linux ARM](https://manjaro.org/download/#ARM)

[Arch Linux ARM](https://archlinuxarm.org/platforms/armv8/broadcom/raspberry-pi-4)

[Ubuntu MATE for Raspberry Pi](https://ubuntu-mate.org/ports/raspberry-pi/)

[Ubuntu Desktop for Raspberry Pi](https://ubuntu.com/raspberry-pi)

[Ubuntu Core on a Raspberry Pi](https://ubuntu.com/download/raspberry-pi-core)

[Ubuntu Server for ARM](https://ubuntu.com/download/server/arm)

[Fedora ARM](https://arm.fedoraproject.org)

[Kali Linux for the Raspberry Pi](https://www.kali.org/docs/arm/kali-linux-raspberry-pi/)

[Twister OS](https://twisteros.com/)

[TitusPi](https://github.com/ChrisTitusTech/TitusPi)

[RetroArch](https://www.retroarch.com/?page=platforms)

[RetroPie](https://retropie.org.uk/)

[LibreELEC](https://libreelec.tv/)

[OSMC](https://osmc.tv)

[RISC OS](https://www.riscosopen.org/content/)

[DietPi](https://github.com/MichaIng/DietPi)


# Raspberry Pi Tools

[Back to the Top](https://github.com/mikeroyal/raspberry-pi-Guide/blob/main/README.md#table-of-contents)

[Raspberry Pi Imager](https://www.raspberrypi.org/software/) is the quick and easy way to install Raspberry Pi OS and other operating systems to a microSD card, ready to use with your Raspberry Pi.

[Raspberry Pi Locator](https://rpilocator.com/) is a website to track Raspberry Pi 4 model B, Compute Module 4, Pi Zero 2 W, and Pico availability across multiple retailers in different countries.

[Raspberry Pi Network Install (Beta)](https://www.raspberrypi.com/documentation/computers/getting-started.html#installing-over-the-network-beta) is a feature can be used to start the Raspberry Pi Imager application directly on a Raspberry Pi 4, or a Raspberry Pi 400, by downloading it from the internet using an Ethernet cable. The Raspberry Pi Imager application, which will run in memory on your Raspberry Pi, can then be used to flash the operating system onto a blank SD Card or USB disk, just like normal. 

[Raspberry Pi Bootloader](https://www.raspberrypi.com/documentation/computers/raspberry-pi.html#updating-the-bootloader) is a feature, which is now available in beta, that utilize an **EEPROM(Electrically Erasable Programmable Read-Only Memory)** to store the system’s bootloader. This EEPROM is persistent storage that is located on the Pi’s mainboard. The advantage of using the EEPROM instead is that the Raspberry Pi 4 can perform tasks without needing any storage to be attached.

[Pi-Apps](https://github.com/Botspot/pi-apps) is a Raspberry Pi App Store for Open Source Projects.

[Backup Raspberry Pi Server](https://github.com/geerlingguy/backup-pi) is an Ansible configuration to set up a Raspberry Pi as a backup server for storing backups of data from other servers (e.g. webroots, files, and databases). This project is developed and maintained by [Jeff Geerling](https://github.com/geerlingguy).
 
[RaspiBackup](https://github.com/framps/raspiBackup) is a tool that backups and restores your running Raspberry.

[Proxmox VE](https://www.home-assistant.io/integrations/proxmoxve/) is an open-source server virtualization environment. 

[Pimox](https://github.com/pimox/pimox7) is a port of Proxmox to the Raspberry Pi allowing you to build a Proxmox cluster of Rapberry Pi's or even a hybrid cluster of Pis and x86 hardware.

[PiKVM](https://github.com/pikvm/pikvm) is a very simple and fully functional Raspberry Pi-based KVM over IP.

[Pi-hole](https://pi-hole.net/) is a [DNS sinkhole](https://en.wikipedia.org/wiki/DNS_Sinkhole) that protects your devices from unwanted content, without installing any client-side software, intended for use on a private network. It is designed for use on embedded devices with network capability, such as the Raspberry Pi, but it can be used on other machines running Linux and cloud implementations.

[Etcher](https://www.balena.io/etcher/) is an open source, cross-platform software that makes it easy to flash operating system images to a microSD card or USB device.

[PiShrink](https://github.com/Drewsif/PiShrink) is a bash script that automatically shrink a pi image that will then resize to the max size of the SD card on boot. 

[Gpiozero](https://github.com/gpiozero/gpiozero) is a simple interface to GPIO(General-Purpose Input/Output) devices with the Raspberry Pi.

[Kubernetes on ARM](https://github.com/luxas/kubernetes-on-arm) is a tool to get your ARM device up and running Kubernetes in less than ten minutes.

## File systems

[Back to the Top](#table-of-contents)

[GlusterFS](https://www.gluster.org/) is a free and open source scalable network filesystem. Gluster is a scalable network filesystem. Using common off-the-shelf hardware, you can create large, distributed storage solutions for media streaming, data analysis, and other data- and bandwidth-intensive tasks.

[Ceph](https://ceph.io/) is a software-defined storage solution designed to address the object, block, and file storage needs of data centers adopting open source as the new norm for high-growth block storage, object stores and data lakes. Ceph provides enterprise scalable storage while keeping [CAPEX](https://corporatefinanceinstitute.com/resources/knowledge/modeling/how-to-calculate-capex-formula/) and [OPEX](https://www.investopedia.com/terms/o/operating_expense.asp) costs in line with underlying bulk commodity disk prices.

[Hadoop Distributed File System (HDFS)](https://www.ibm.com/analytics/hadoop/hdfs) is a distributed file system that handles large data sets running on commodity hardware. It is used to scale a single Apache Hadoop cluster to hundreds (and even thousands) of nodes. HDFS is one of the major components of Apache Hadoop, the others being [MapReduce](https://www.ibm.com/analytics/hadoop/mapreduce) and [YARN](https://hadoop.apache.org/docs/current/hadoop-yarn/hadoop-yarn-site/YARN.html).

[ZFS](https://docs.oracle.com/cd/E19253-01/819-5461/zfsover-2/) is an enterprise-ready open source file system and volume manager with unprecedented flexibility and an uncompromising commitment to data integrity.

[OpenZFS](https://openzfs.org/wiki/Main_Page ) is an open-source storage platform. It includes the functionality of both traditional file systems and volume manager. It has many advanced features including:

  - Protection against data corruption.
  - Integrity checking for both data and metadata.
  - Continuous integrity verification and automatic "self-healing" repair.

[Btrfs](https://btrfs.wiki.kernel.org/index.php/Main_Page) is a modern copy on write (CoW) filesystem for Linux aimed at implementing advanced features while also focusing on fault tolerance, repair and easy administration. Its main features and benefits are:

  - Snapshots which do not make the full copy of files
  - RAID - support for software-based RAID 0, RAID 1, RAID 10
  - Self-healing - checksums for data and metadata, automatic detection of silent data corruptions
  
[MergerFS](https://github.com/trapexit/mergerfs) is a union filesystem geared towards simplifying storage and management of files across numerous commodity storage devices. It is similar to mhddfs, unionfs, and aufs.

**MergerFS Features**

  - Configurable behaviors / file placement
  - Ability to add or remove filesystems at will
  - Resistance to individual filesystem failure
  - Support for extended attributes (xattrs)
  - Support for file attributes (chattr)
  - Runtime configurable (via xattrs)
  - Works with heterogeneous filesystem types
  - Moving of file when filesystem runs out of space while writing
  - Ignore read-only filesystems when creating files
  - Turn read-only files into symlinks to underlying file
  - Hard link copy-on-write / CoW
  - Support for POSIX ACLs
  
[Bcachefs](https://bcachefs.org/) is an advanced new filesystem for Linux, with an emphasis on reliability and robustness and the complete set of features one would expect from a modern filesystem. Scalability has been tested to 50+ TB, will eventually scale far higher. 

[Squashfs](https://www.kernel.org/doc/html/latest/filesystems/squashfs.html) is a compressed read-only filesystem for Linux. It uses zlib, lz4, lzo, or xz compression to compress files, inodes and directories. Inodes in the system are very small and all blocks are packed to minimize data overhead.

[NTFS(New Technology File System)](https://docs.microsoft.com/en-us/windows-server/storage/file-server/ntfs-overview) is the primary file system for recent versions of Windows and Windows Server—provides a full set of features including security descriptors, encryption, disk quotas, and rich metadata, and can be used with Cluster Shared Volumes (CSV) to provide continuously available volumes that can be accessed simultaneously from multiple nodes of a failover cluster.

[exFAT(Extended File Allocation Table )](https://docs.microsoft.com/en-us/windows/win32/fileio/exfat-specification) is the file system that was the successor to FAT32 in the FAT family of file systems. It was optimized for flash memory such as USB flash drives and SD cards.

## Tools for Home Automation

[Back to the Top](https://github.com/mikeroyal/raspberry-pi-Guide/blob/main/README.md#table-of-contents)

[Home Assistant](https://www.home-assistant.io/) is an open source home automation that puts local control and privacy first. Home Assistant is powered by a worldwide community of tinkerers and DIY enthusiasts that runs great on Raspberry Pi. 

[ESPHome](https://esphome.io/) is a system to control your ESP8266/ESP32 by simple yet powerful configuration files and control them remotely through Home Automation systems.
Automation systems.

[Shelly Cloud](https://shelly.cloud/) is a Smart home control tool that has been perfected and provides precise monitoring of your Shelly devices no matter where you are. Shelly devices are compatible with Alexa, Google Home, Android, and iOS. 

[Plex media server](https://www.plex.tv/) is a application that gives you the power to add, access and share all the entertainment that matters to you, on almost any device. With 50,000+ on demand titles and hundreds of channels of live TV, plus your own personal media collection, using one powerful app.

[Amazon Alexa](https://alexa.amazon.com/) is a smart virtual assistant software to manage Alexa-enabled devices, control music playback, view shopping lists on the go, keep track of upcoming reminders, check on active timers and much more. 

[Google Assistant](https://assistant.google.com/) is a smart virtual assistant software on mobile and home automation devices.

[Apple HomeKit](https://www.apple.com/shop/accessories/all/homekit) is a software framework that enables your app to coordinate and control home automation accessories from multiple vendors to present a coherent, user-focused interface. Using HomeKit, your app can: Discover HomeKit-compatible automation accessories and add them to a persistent, cross-device home configuration database.

[Samsung SmartThings](https://www.smartthings.com/) is a sofwtare frmaeowrk that you can connect, monitor and control multiple smart home devices quicker and easier. Connect your Samsung smart TVs, smart appliances, smart speakers and brands like Ring, Nest and Philips Hue all from one app.

[Ecobee](https://www.ecobee.com) is a home automation company in Canada that makes thermostats for residential and commercial use.

[Lutron Caséta](https://www.lutron.com/en-US/Products/Pages/SingleRoomControls/CasetaWireless/Overview.aspx) is a smart lighting control system that is a great solution for giving any client smart lighting control. It was purposely built to work in homes of all ages and it works with older wiring as well as new.

[Philips Hue](https://www.philips-hue.com) is  a smart lighting system. The smart lights, Hue Bridge, and smart controls will forever change the way you experience light.

[Sonos](https://www.sonos.com) is the wireless home sound system that fills as many rooms as you want with great-sounding music, movies, and TV. 

[MQTT](https://mqtt.org/) is an [OASIS standard](https://www.oasis-open.org/standards/) messaging protocol for the Internet of Things (IoT). It is designed as an extremely lightweight publish/subscribe messaging transport that is ideal for connecting remote devices with a small code footprint and minimal network bandwidth.

[Zigbee](https://csa-iot.org/all-solutions/zigbee/) is the full-stack, secure, reliable, and market-proven solution used by a majority of large smart home ecosystem providers, such as Amazon's Echo Plus, Samsung SmartThings, Signify (Philips Hue), and more.

[openHAB](https://github.com/openhab) is a cross-platform software with the aim to integrate all kinds of Smart Home technologies, devices, etc. 

[Z-Wave](https://www.z-wave.com/) is the leading wireless communications protocol behind many of the secure, trusted brands that are working to make everyone's home smarter and safer.

[Gladys Assistant](https://github.com/gladysassistant/gladys) is a  privacy-first, open-source home assistant and runs great on Raspberry Pi.

[Kodi for Raspberry Pi](https://kodi.tv/download/853) is a free and open source media player application developed by the XBMC/Kodi Foundation.

[Pi-hole](https://pi-hole.net/) is a [DNS sinkhole](https://en.wikipedia.org/wiki/DNS_Sinkhole) that protects your devices from unwanted content, without installing any client-side software, intended for use on a private network. It is designed for use on embedded devices with network capability, such as the Raspberry Pi, but it can be used on other machines running Linux and cloud implementations.

[AdGuard Home](https://github.com/AdguardTeam/AdGuardHome) is a DNS relay station with ad/tracker/other blocking, IP address redirections, and DNS-over-HTTPS.

[FreeRDP](https://github.com/FreeRDP/FreeRDP) is a free remote desktop protocol library and clients.

[Pimox](https://github.com/pimox/pimox7) is a port of Proxmox to the Raspberry Pi allowing you to build a Proxmox cluster of Rapberry Pi's or even a hybrid cluster of Pis and x86 hardware.

[PiKVM](https://github.com/pikvm/pikvm) is a very simple and fully functional Raspberry Pi-based KVM over IP.

[Rustdesk](https://rustdesk.com/) is an open source virtual/remote desktop infrastructure for everyone. Display and control your PC (Windows, macOS, and Linux) and Android devices. 

[TinyPilot](https://tinypilotkvm.com/) is a tool that enables KVM over IP letting you control any computer remotely.

[PM2](https://github.com/Unitech/pm2) is a production process manager for Node.js applications with a built-in load balancer. It allows you to keep applications alive forever, to reload them without downtime and to facilitate common system admin tasks.

[authentik](https://github.com/goauthentik/authentik) is an open-source Identity Provider focused on flexibility and versatility. You can use authentik in an existing environment to add support for new protocols. authentik is also a great solution for implementing signup/recovery/etc in your application, so you don't have to deal with it.

[RPiPlay](https://github.com/FD-/RPiPlay) is an open-source implementation of an AirPlay mirroring server for the Raspberry Pi that supports iOS 9 and later.

[Lightberry](https://lightberry.eu) is a Led lighting solution dedicated for raspberry pi and your TV.

[Lomorage](https://github.com/lomorage/homepage) is a Private photo cloud host on Raspberry Pi, with Android/iOS/Web client.

[Balena Sound](https://sound.balenalabs.io/) is a single or multi-room streamer for an existing audio device using a Raspberry Pi! It supports Bluetooth, Airplay and Spotify Connect.

[OpenBalena](https://balena.io/open) is a platform to deploy and manage connected devices.

## Home Assistant
[Back to the Top](https://github.com/mikeroyal/Raspberry-Pi-Guide#table-of-contents)
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/177719719-9108f14f-9ca0-45e4-b1f5-55efaf1803e6.png">
  <br />
</p>

[Home Assistant](https://home-assistant.io/hassio/) is a container-based system for managing your Home Assistant Core installation and related applications. The system is controlled via Home Assistant which communicates with the Supervisor. The Supervisor provides an API to manage the installation. This includes changing network settings or installing and updating software.

**Quick Links**

 - [Getting Started with Home Assistant](https://home-assistant.io/getting-started)
 - [Home Assistant for Raspberry Pi](https://www.home-assistant.io/installation/raspberrypi/)
 - [Installing Home Assistant OS using Proxmox 7](https://github.com/Kanga-Who/home-assistant/blob/master/Home%20Assistant%20with%20Proxmox%20installation.md)

[Home Assistant Frontend](https://demo.home-assistant.io/) is a frontend for Home Assistant. 

### Tools to write the HA image to your boot media(microSD card or USB device)

[Raspberry Pi Imager](https://www.raspberrypi.org/software/) is the quick and easy way to install Raspberry Pi OS and other operating systems to a microSD card, ready to use with your Raspberry Pi.

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/177719735-575326e7-3f29-4175-8ca1-b9eabb15e2e6.png">
  <br />
</p>

[Etcher](https://www.balena.io/etcher/) is an open source, cross-platform software that makes it easy to flash operating system images to a microSD card or USB device.

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/177719741-a88c162f-bfa9-469f-a87e-e9f12c175e07.png">
  <br />
</p>

### Home Assistant integrations

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/177719765-602b4658-c8bf-4952-a238-4b986efbb7cb.png">
  <br />
</p>

Home Assistant integrations. Credit: [Home Assistant](https://www.home-assistant.io/integrations/)

[ESPHome](https://esphome.io/) is a system to control your ESP8266/ESP32 by simple yet powerful configuration files and control them remotely through Home Automation systems.

[Shelly Cloud](https://shelly.cloud/) is a Smart home control tool that has been perfected and provides precise monitoring of your Shelly devices no matter where you are. Shelly devices are compatible with Alexa, Google Home, Android, and iOS. 

[Plex media server](https://www.plex.tv/) is a application that gives you the power to add, access and share all the entertainment that matters to you, on almost any device. With 50,000+ on demand titles and hundreds of channels of live TV, plus your own personal media collection, using one powerful app.

[Amazon Alexa](https://alexa.amazon.com/) is a smart virtual assistant software to manage Alexa-enabled devices, control music playback, view shopping lists on the go, keep track of upcoming reminders, check on active timers and much more. 

[Google Assistant](https://assistant.google.com/) is a smart virtual assistant software on mobile and home automation devices.

[Apple HomeKit](https://www.apple.com/shop/accessories/all/homekit) is a software framework that enables your app to coordinate and control home automation accessories from multiple vendors to present a coherent, user-focused interface. Using HomeKit, your app can: Discover HomeKit-compatible automation accessories and add them to a persistent, cross-device home configuration database.

[Samsung SmartThings](https://www.smartthings.com/) is a sofwtare frmaeowrk that you can connect, monitor and control multiple smart home devices quicker and easier. Connect your Samsung smart TVs, smart appliances, smart speakers and brands like Ring, Nest and Philips Hue all from one app.

[Ecobee](https://www.ecobee.com) is a home automation company in Canada that makes thermostats for residential and commercial use.

[Lutron Caséta](https://www.lutron.com/en-US/Products/Pages/SingleRoomControls/CasetaWireless/Overview.aspx) is a smart lighting control system that is a great solution for giving any client smart lighting control. It was purposely built to work in homes of all ages and it works with older wiring as well as new.

[Philips Hue](https://www.philips-hue.com) is  a smart lighting system. The smart lights, Hue Bridge, and smart controls will forever change the way you experience light.

[Sonos](https://www.sonos.com) is the wireless home sound system that fills as many rooms as you want with great-sounding music, movies, and TV. 

[MQTT](https://mqtt.org/) is an [OASIS standard](https://www.oasis-open.org/standards/) messaging protocol for the Internet of Things (IoT). It is designed as an extremely lightweight publish/subscribe messaging transport that is ideal for connecting remote devices with a small code footprint and minimal network bandwidth.

[Zigbee](https://csa-iot.org/all-solutions/zigbee/) is the full-stack, secure, reliable, and market-proven solution used by a majority of large smart home ecosystem providers, such as Amazon's Echo Plus, Samsung SmartThings, Signify (Philips Hue), and more.

[openHAB](https://github.com/openhab) is a cross-platform software with the aim to integrate all kinds of Smart Home technologies, devices, etc. 

[Z-Wave](https://www.z-wave.com/) is the leading wireless communications protocol behind many of the secure, trusted brands that are working to make everyone's home smarter and safer.

[Zwavejs2Mqtt](https://zwave-js.github.io/zwavejs2mqtt/) is a fully configurable Zwave to MQTT Gateway and Control Panel Web UI.

[Z-Wave JS Server](https://github.com/zwave-js/zwave-js-server) is a small server wrapper around Z-Wave JS to access it via a WebSocket.

[Z-Wave JS Config DB Browser](https://devices.zwave-js.io/) is the official device configuration reference to find out if your device is supported. Currently supports 387 brands, spanning at least 2075 device configurations.

## Homebridge
[Back to the Top](https://github.com/mikeroyal/raspberry-pi-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/177946864-bd962065-a863-4f97-b6be-a8f98861efa4.png">
  <br />
</p>

[Homebridge](https://homebridge.io/) is a software frameowrk that allows you to integrate with smart home devices that do not natively support [HomeKit](https://www.apple.com/shop/accessories/all/homekit). There are over 2,000 Homebridge plugins supporting thousands of different smart accessories. 

- [Official Homebridge Raspberry Pi Image](https://github.com/homebridge/homebridge-raspbian-image/wiki/Getting-Started)
- [Setup Homebridge on a Raspberry Pi (Raspbian)](https://github.com/homebridge/homebridge/wiki/Install-Homebridge-on-Raspbian)
- [Setup Homebridge on Debian or Ubuntu](https://github.com/homebridge/homebridge/wiki/Install-Homebridge-on-Debian-or-Ubuntu-Linux)
- [Setup Homebridge on Red Hat, CentOS Stream or Fedora](https://github.com/homebridge/homebridge/wiki/Install-Homebridge-on-Red-Hat%2C-CentOS-or-Fedora-Linux) 
- [Setup Homebridge on Docker (Linux)](https://github.com/homebridge/homebridge/wiki/Install-Homebridge-on-Docker)


### Tools to write the Homebridge image to your boot media(microSD card or USB device)

[Raspberry Pi Imager](https://www.raspberrypi.org/software/) is the quick and easy way to install Raspberry Pi OS and other operating systems to a microSD card, ready to use with your Raspberry Pi.

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/177719735-575326e7-3f29-4175-8ca1-b9eabb15e2e6.png">
  <br />
</p>

[Etcher](https://www.balena.io/etcher/) is an open source, cross-platform software that makes it easy to flash operating system images to a microSD card or USB device.

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/177719741-a88c162f-bfa9-469f-a87e-e9f12c175e07.png">
  <br />
</p>

[Homebridge UI](https://github.com/oznu/homebridge-config-ui-x) is a tool that provides an easy to use interface to manage your Homebridge plugins, configuration and accessories.

   - Install and configure Homebridge plugins.
   - Monitor your Homebridge server via a fully customisable widget-based dashboard.
   - View and control Homebridge accessories.
   - Backup and Restore your Homebridge instance.
    
  <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/177949596-0d02c572-fa6b-4fc7-adbd-d136f81149fb.png">
  <br />
  Homebridge UI
 </p> 
 
## ESPHome

[Back to the Top](#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/178136653-b6e635f6-5fa9-40a6-9903-e0dfb912ed80.png">
  <br />
</p>

[ESPHome](https://esphome.io/) is a system to control your ESP8266/ESP32 by simple yet powerful configuration files and control them remotely through Home Automation systems.

#### Quick Links

 - [ESP Web Tools](https://esphome.github.io/esp-web-tools/)

 - [Installing ESPHome Manually | ESPHome](https://esphome.io/guides/installing_esphome.html)
 
 - [Getting Started with the ESPHome Command Line](https://esphome.io/guides/getting_started_command_line.html)
 
 - [Getting Started with ESPHome and Home Assistant](https://esphome.io/guides/getting_started_hassio.html)
 
 - [ESPHome on the Raspberry Pi Pico! | Jeff Geerling](https://www.jeffgeerling.com/blog/2022/esphome-on-raspberry-pi-pico)
 
 - [How to Start on Raspberry Pi Home Automation | ESPHome](https://www.instructables.com/How-to-Start-on-Raspberry-Pi-Home-Automation-ESPHo/)

 - [ESPHome Setup | Integrating Home Assistant with Adafruit IO](https://learn.adafruit.com/integrating-adafruit-io-with-home-assistant/esphome-setup)

### Install ESPHome using Home Assistant

In [Home Assistant](https://www.home-assistant.io/integrations/esphome/) go to: 

  **Configuration > Add-ons, Backups & Supervisor > Add-on Store (button in the lower right corner) or click on the My Home Assistant Link below:**

Open your Home Assistant instance and show the Supervisor add-on store.

[![ESPHome HA](https://user-images.githubusercontent.com/45159366/178136849-9a5deed7-beb8-4a62-aeda-ce9aec3fac3e.svg)](https://my.home-assistant.io/redirect/config_flow_start?domain=esphome)

   -  Next, search for ESPHome, click on the result and then click on the Install button. 
   
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/178137323-40fb0ec9-f35c-43d7-b60c-08588c89fd33.png">
  <br />
</p>
   
   -  When the installation is finished, the Install button will be replaced with Start button – click on it to start the ESPHome add-on. 
   
<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/178137277-b71897d5-2684-451c-af2f-ab85f9b1affa.png">
  <br />
</p>

   -  Wait a few seconds for the ESPHome to start and then click on the Open Web UI button.
   
<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/178137097-7753aed9-c3e7-4fba-9b52-570771609572.png">
  <br />
</p>
   
### Install ESPHome using Docker

  - First thing is to pull the [ESPHome Docker image from Docker Hub](https://hub.docker.com/u/esphome) (Online). 

    ```docker pull esphome/esphome```

  - Then, start the ESPHome wizard. This wizard will ask you about your device type, your device name, your WiFi credentials and finally will generate a yaml file containing all of the configurations for you. 
   
   ```docker run --rm -v "${PWD}":/config -it esphome/esphome wizard stl.yaml```
  
   -  Now, connect your ESP device to the device where Docker is running (either using an USB cable or Serial-To-USB adapter) and if you are on Linux type the following command :

   ```dmesg | grep ttyUSB```
   
   - Put your device in programming mode (if needed) and execute the next command to install the ESPHome on the device connected to the /dev/ttyUSB1 using the configuration stored in stl.yaml file 
   
  ```docker run --rm -v "${PWD}":/config --device=/dev/ttyUSB1 -it esphome/esphome run stl.yaml```
   
### Install ESPHome using Python

 - If you are on macOS or Linux check if Python 3.8 or later is installed by executing the command.
  
 ```python3 --version```
  
 - If you are on macOS, you need to install wheel and esphome packages by using the following command.
  
 ```pip3 install wheel esphome```
  
 - If you are on Linux, you have to install esphome package by using the following command.
  
  ```pip3 install --user esphome```
   
 - If you are on macOS or Linux you can start the ESPHome wizard using the following command.
  
  ```esphome wizard stl-python.yaml```
   
 - Finally, connect your ESP device to your Computer (using USB cable or Serial-To-usb adapter) and put it in programming mode (if needed). Then, Install ESPHome using the configuration in the stl-python.yaml file.
  
  ```esphome run stl-python.yaml```
  
## Turning Raspberry Pi into a Router

[Back to the Top](#table-of-contents)

### Software

[OpenWrt Project](https://openwrt.org/) is a Linux operating system targeting embedded devices. Instead of trying to create a single, static firmware, OpenWrt provides a fully writable filesystem with package management. It's primarily used on embedded devices to route network traffic.

  * [OpenWrt Wiki - Raspberry Pi setup](https://openwrt.org/toh/raspberry_pi_foundation/raspberry_pi)

**Download the appropriate OpenWrt image for your Raspberry PI by going to the link above.**

### Tools to write the Homebridge image to your boot media(microSD card)

[Raspberry Pi Imager](https://www.raspberrypi.org/software/) is the quick and easy way to install Raspberry Pi OS and other operating systems to a microSD card, ready to use with your Raspberry Pi.

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/177719735-575326e7-3f29-4175-8ca1-b9eabb15e2e6.png">
  <br />
</p>

### Hardware

[Raspberry Pi Router Board for CM4 module (Cost: $55 USD)](https://www.seeedstudio.com/CM4-Router-Board-p-5211.html) is an expansion board based on the Raspberry Pi Compute Module 4. It brings Raspberry Pi CM4 two full-speed gigabit network ports and offers better performance, lower CPU usage, and higher stability for a long time work compared with a USB network card. It's compatible with [Raspberry Pi OS](https://www.raspberrypi.com/software/operating-systems/), [Ubuntu Server](https://ubuntu.com/download/raspberry-pi) and other Raspberry Pi systems.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/183271470-728741bd-0d52-480d-8ebe-8c9817589093.png">
  <br />
  Raspberry Pi Router Board for CM4 module
</p>

**Technical Specs:**

 * Compatible Module: Raspberry Pi Compute Module 4 series.
 * BCM2711 4 core @ 1.5GHz Cortex-A72.
 * Support standard Raspberry Pi HAT interface.
 * Support POE HAT to supply power to the board.
 * Support POE HAT for external power supply.
 * Full-speed dual gigabit network interface.
 * Master-slave dual USB2.0 interface.
 * Micro SD card slot, used to support non-eMMC version of CM4.
 * Standard HDMI video output interface.
 * 0.91 inch IIC OLED display.
 * 5V DC fan interface(Support controlling via PWM signal).
 * Ethernet: high-performance Gigabit ethernet controller RTL8111E chip, JXD 2111x G2406s chip as isolation transformer.
   * Port0: Compute Module 4 Built-In.
   * Port1: PCI Express 1000BASE-T NIC.
 * GPIO: 40-Pin GPIO compatible with Raspberry Pi.

## Setting Watchdog Timer (WDT) on Raspberry Pi
[Back to the Top](https://github.com/mikeroyal/raspberry-pi-Guide#table-of-contents)

[Watchdog Timer (WDT)](https://en.wikipedia.org/wiki/Watchdog_timer) is a timer that monitors microcontroller (MCU) programs to see if they are out of control or have stopped operating.

### Installing and enabling WDT service

To enable watchdog you have to change the boot parameters by adding **dtparam=watchdog=on** in **/boot/config.txt** using a text editor such as nano, vim, gedit, etc.. Also, install watchdog package and enable it to start at startup. Also, make sure to restart your Raspberry Pi for these settings to take effect.

```pi@raspberrypi:~ $ sudo apt install watchdog```

```pi@raspberrypi:~ $sudo systemctl enable watchdog```

### Configure WDT service

Configuration file for watchdog can be found in **/etc/watchdog.conf**. 

```
max-load-1 = 24
watchdog-device = /dev/watchdog
realtime = yes
priority = 1
```

**To start the WTD service:**

```pi@raspberrypi:~ $ sudo systemctl start watchdog```

**Check watchdog status:**

```pi@raspberrypi:~ $ sudo systemctl status watchdog```

**To stop the service:**

```pi@raspberrypi:~ $ sudo systemctl stop watchdog```

# Raspberry Pi Upgrades

[Back to the Top](https://github.com/mikeroyal/Raspberry-Pi-Guide/blob/main/README.md#table-of-contents)

[NexDock](https://nexdock.com/features/) is an accessory with a HDMI-in port and Type-C cable NexDock that turns the Raspberry Pi 4 into a fully functional computer.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/163285466-194e0d69-f68d-4c82-9cd6-f7832d9f1582.jpg">
</p>

[Raspberry Pi Cases from Pi-Shop US](https://www.pishop.us/product-category/raspberry-pi/pi-cases/)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/112692629-80803580-8e3c-11eb-8b5c-c4879113a058.png">
</p>


[Raspberry Pi Cases from The Pi Hut](https://thepihut.com/collections/raspberry-pi-cases)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/112692621-7eb67200-8e3c-11eb-9a88-ae72443701ce.png">
</p>

[X825 expansion board](https://www.amazon.com/Geekworm-Raspberry-Storage-Expansion-Compatible/dp/B07VXF2HJG) provides a complete storage solution for newest Raspberry Pi 4 Model B, it supports up to 4TB 2.5-inch SATA hard disk drives (HDD) / solid-state drive (SSD).

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/112692608-7bbb8180-8e3c-11eb-80f6-1b1d9d8656e0.png">
</p>


[Sabrent M.2 SSD [NGFF] to USB 3.0 / SATA III 2.5-Inch Aluminum Enclosure Adapter](https://www.amazon.com/Sabrent-2-5-Inch-Aluminum-Enclosure-EC-M2CU/dp/B07924J5NT/ref=sr_1_10?crid=28O2JRHO9DE4G&dchild=1&keywords=m.2+to+usb+3.0+adapter&qid=1616632834&sprefix=m.2+to+usb,aps,236&sr=8-10)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/112692658-88d87080-8e3c-11eb-81f1-1c796145cf7a.png">
</p>


[Samsung 970 EVO 250GB - NVMe PCIe M.2 2280 SSD](https://www.amazon.com/dp/B07BN5FJZQ/ref=twister_B08KGF1DPF?_encoding=UTF8&psc=1)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/112692666-8c6bf780-8e3c-11eb-85a6-1f160a10a01a.png">
</p>


[Western Digital 1TB WD Blue SN550 NVMe Internal SSD](https://www.amazon.com/dp/B07YFF8879/ref=twister_B082KVPKQ5?_encoding=UTF8&psc=1)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/112692675-8d9d2480-8e3c-11eb-9ed1-e08c2932d5ab.png">
</p>


[SAMSUNG T5 Portable SSD](https://www.amazon.com/Samsung-500GB-Portable-Solid-State/dp/B074WZJ4MF/ref=sr_1_4?crid=343DRDX8SJJV6&dchild=1&keywords=samsung+t5+portable+ssd&qid=1616632092&sprefix=samsung+t5+portable,aps,374&sr=8-4)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/112692679-8ece5180-8e3c-11eb-94e5-18796639776e.png">
</p>


[Samsung SSD 860 EVO 250GB mSATA Internal SSD](https://www.amazon.com/Samsung-250GB-mSATA-Internal-MZ-M6E250BW/dp/B07864YNTZ/ref=sr_1_8?crid=2KRBSPRQYUIOH&dchild=1&keywords=samsung+850+evo+msata&qid=1616632277&sprefix=samsung+850+evo+m,aps,233&sr=8-8)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/112692689-91c94200-8e3c-11eb-82ed-28d6ab05c072.png">
</p>


[Samsung 850 EVO 120GB SSD mSATA](https://www.amazon.com/Samsung-850-120GB-mSATA-MZ-M5E120BW/dp/B00TGIVQ4G/ref=sr_1_9?crid=2KRBSPRQYUIOH&dchild=1&keywords=samsung+850+evo+msata&qid=1616632277&sprefix=samsung+850+evo+m,aps,233&sr=8-9)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/112692696-92fa6f00-8e3c-11eb-8c7a-c169bb0c9b1e.png">
</p>


# Getting Software

[Back to the Top](https://github.com/mikeroyal/Raspberry-Pi-Guide/blob/main/README.md#table-of-contents)

## App Outlet

[App Outlet](https://app-outlet.github.io/) is a Universal application store(Flatpaks, Snaps, and AppImages) inspired by the Linux App Store online service.

 <img src="https://user-images.githubusercontent.com/45159366/106686354-0095c780-657f-11eb-892b-659d3252d6e7.png">
 
 ## Flatpaks

[FlatHub](https://flathub.org/) is a build and distribution service for Flatpak applications.

[FlatHub Forum](https://discourse.flathub.org/)

 <img src="https://user-images.githubusercontent.com/45159366/106686365-055a7b80-657f-11eb-9b58-1de28abe2e5b.png">
 
 ## Snaps

[Snap Store](https://snapcraft.io/store) is a build and distribution service for Snap applications.

[Snapcraft Forum](https://forum.snapcraft.io/)

 <img src="https://user-images.githubusercontent.com/45159366/106686375-08ee0280-657f-11eb-9918-5385d8c09148.png">
 <img src="https://user-images.githubusercontent.com/45159366/106686378-0a1f2f80-657f-11eb-83aa-37ac96c7b032.png">

## AppImages

[AppImageHub](https://www.appimagehub.com) is a build and distribution service for AppImage applications.

[AppImage Manager](https://github.com/AppImageCrafters/appimage-manager) is a package manager for AppImages.

[AppImage Forum](https://discourse.appimage.org/)

 <img src="https://user-images.githubusercontent.com/45159366/106686382-0b505c80-657f-11eb-9d74-9a94ec0d0693.png">
 
# Using Android Apps on Raspberry Pi

[Back to the Top](https://github.com/mikeroyal/Raspberry-Pi-Guide/blob/main/README.md#table-of-contents)

[Waydroid](https://github.com/waydroid/waydroid) is a container-based approach to boot a full Android system on a regular Linux system. The Android runtime environment ships with a minimal customized Android system image based on LineageOS. The image is currently based on Android 10.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/171924198-0d440de1-9ff7-4e37-b6c3-f7e42c266530.png">
</p>

[LineageOS](https://lineageos.org/) is a free and open-source operating system for various devices, based on the Android mobile platform.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/108647222-f0ca1e80-746c-11eb-8e55-0e9808bb24fc.png">
</p>

[Scrcpy](https://github.com/Genymobile/scrcpy) is an application by Genymotion that provides display and control of Android devices connected on USB (or over TCP/IP). It does not require any root access and works on GNU/Linux, Windows and macOS. The Android device requires at least API 21 (Android 5.0).

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/108637389-396ae300-743f-11eb-971a-f5b554033552.jpg">
</p>

# Gaming
[Back to the Top](https://github.com/mikeroyal/Raspberry-Pi-Guide#table-of-contents)

## Steam
**Open the terminal and copy/paste command below**

```sh
wget https://steamcdn-a.akamaihd.net/client/installer/steam.deb
```
[Proton](https://github.com/ValveSoftware/Proton/) is a tool for use with the Steam client which allows games which are exclusive to Windows to run on the Linux operating system. It uses Wine to facilitate this.

## Enable Proton in Steam

 - Click on “Steam” then “Settings” to open the Settings window at the far-left corner.
 - On the “Settings” window, click on “Steam Play.” Ensure you check the “Enable Steam Play for supported files” and “Enable Steam Play for   all other titles” checkboxes. Lastly, select the Proton version you wish to use from the drop-down menu.
 
 <img src="https://user-images.githubusercontent.com/45159366/106686402-13100100-657f-11eb-9012-6bdac264a808.png">
 
## ProtonDB
[Back to the Top](https://github.com/mikeroyal/Raspberry-Pi-Guide#table-of-contents)

[ProtonDB](https://www.protondb.com) is a collection of over 100,000 gaming reports from other gamers as they test games with Proton on Linux and provide aggregate scores of how well games perform. A growing pool of suggestions provides tweaks that you can try to get games working while Proton continues development. In addition to this, you may explore the Steam game catalog on this site to browse and discover a wide range of titles that were previously unavailable for use on Linux.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/108773213-dcd8f800-7512-11eb-8775-19b0c8924d55.png">
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/108773214-dd718e80-7512-11eb-983b-ce192e5b30f2.png">
</p>

## Lutris
[Back to the Top](https://github.com/mikeroyal/Raspberry-Pi-Guide#table-of-contents)

[Lutris](https://lutris.net) is a gaming client for Linux. It gives you access to all your video games with the exception of the current console generation. Also, integrates nicely with other stores like GOG, Steam, Battle.net, Origin, Uplay and many other sources that allow you to import your existing game library and community maintained install scripts give you a completely automated setup.

[Add Epic Games Store](https://lutris.net/games/epic-games-store/)

 <img src="https://user-images.githubusercontent.com/45159366/106686406-14412e00-657f-11eb-97c4-c80c6e25a374.png">

## Heroic Games Launcher
[Back to the Top](https://github.com/mikeroyal/Raspberry-Pi-Guide#table-of-contents)
 
[Heroic Games Launcher](https://github.com/Heroic-Games-Launcher/HeroicGamesLauncher) is a Native GUI Epic Games Launcher for Linux.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/112693066-35b2ed80-8e3d-11eb-930f-2ff8a8695094.png">
</p>

**Hero Game Launcher UI. Credit: [flavioislima](https://github.com/flavioislima)**

## GameHub
[Back to the Top](https://github.com/mikeroyal/Raspberry-Pi-Guide#table-of-contents)

[GameHub](https://github.com/tkashkin/GameHub) is a unified library for all your games. It allows you to store your games from different platforms into one program to make it easier for you to manage your games.

<img src="https://user-images.githubusercontent.com/45159366/107862734-96451880-6e03-11eb-9b92-9d355b890083.png">

**GameHub supports:**

 - native games for Linux
 - **multiple compatibility layers:**
   - Wine
   - Proton
   - [DOSBox](https://www.dosbox.com/)
   - [RetroArch](https://store.steampowered.com/app/1118310/RetroArch/)
   - [ScummVM](https://www.scummvm.org/)
   - [WineWrap](https://www.gog.com/forum/general/adamhms_linux_wine_wrappers_news_faq_discussion/post1) — a set of preconfigured wrappers for [supported games](https://www.gog.com/forum/general/adamhms_linux_wine_wrappers_news_faq_discussion/post3);
   - custom emulators

 - **multiple game platforms:**
   - [Steam](https://store.steampowered.com/)
   - [GOG](https://www.gog.com/)
   - [Humble Bundle (including Humble Trove)](https://www.humblebundle.com/)
   - [itch.io](https://itch.io/)
   

## Game Streaming
[Back to the Top](https://github.com/mikeroyal/Raspberry-Pi-Guide#table-of-contents)

[Steam Link app](https://store.steampowered.com/steamlink/about) is available free of charge, streaming your Steam PC games to phones, tablets, and TV. 

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/112692999-14ea9800-8e3d-11eb-964a-6bee4e665900.png">
</p>

[Geforce NOW](https://www.nvidia.com/en-us/geforce-now/download/) is NVIDIA's Cloud Gaming Service.

 <img src="https://user-images.githubusercontent.com/45159366/106686391-0f7c7a00-657f-11eb-9d0b-1ebb4d385883.jpeg">

[Moonlight Game Streaming](https://moonlight-stream.org/) is a program that let you stream from your PC games over the Internet with no configuration required. Stream from almost any device, whether you're in another room or miles away from your gaming rig.

<img src="https://user-images.githubusercontent.com/45159366/106686398-11463d80-657f-11eb-841a-d534829ccc3d.png">

[Chiaki](https://git.sr.ht/~thestr4ng3r/chiaki) is a Free and Open Source Software Client for PlayStation 4 and PlayStation 5 Remote Play for Linux, FreeBSD, OpenBSD, Android, macOS, Windows, Nintendo Switch and potentially even more platforms. [Chiaki Flatpak](https://flathub.org/apps/details/re.chiaki.Chiaki)

[Xbox Cloud Gaming](https://www.xbox.com/en-US/xbox-game-pass/cloud-gaming) is Microsoft's cloud-based Xbox game-streaming technology **(currently in Beta)**. **Play games like Forza Horizon 4, Halo 5: Guardians, Gears of War 4, Sea of Thieves, Cuphead, Red Dead Redemption 2, and 100+ other games on your mobile device or Chrome web browser**. Xbox Cloud Gaming does require an [Xbox Game Pass Ultimate](https://www.xbox.com/en-US/xbox-game-pass/cloud-gaming) subscription.

<img src="https://user-images.githubusercontent.com/45159366/108111388-74d56e00-7049-11eb-8aeb-3e5d65f9e832.png">

[Stadia](https://stadia.google.com/games) is Google's gaming platform that lets you instantly play your favorite video games on screens you already own. Game on TVs with Chromecast with Google TV, laptops, desktops, tablets or compatible phones. [Stadia Pro](https://stadia.google.com/) is a subscription($9.99 per month) that unlocks a growing collection of free games to play on Stadia. 

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/162089471-3eb27f98-2366-4117-9af5-93bb126a2c37.png">
</p>

[Parsec](https://parsec.app/cloud-gaming) is a video game streaming platform, which offers a wide variety of games and genres to choose from and provides a high-quality and smooth gameplay. SParsec is developed in order to provide a high-quality smooth gameplay, same time to be free of all ads and in-game purchases.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/166166858-e70ca081-8931-46f3-9dc3-fe9c719d76f8.png">
</p>

[Amazon Luna](https://www.amazon.com/luna/landing-page) is Amazon's Cloud Gaming Service. Amazon Luna is Compatible/Supported on a vartiey of [Devices and Browsers](https://www.amazon.com/gp/help/customer/display.html?nodeId=GUFHUSX8X324T4XE).

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/112693072-364b8400-8e3d-11eb-9df0-d58af7ac9c9c.png">
</p>

## Game Emulators
[Back to the Top](https://github.com/mikeroyal/Raspberry-Pi-Guide#table-of-contents)

[EmulationStation Desktop Edition (ES-DE)](https://www.es-de.org/) is a frontend application for browsing and launching games from your multi-platform game collection. It's  available for Unix/Linux, macOS(M1 & Intel) and Windows.

[RetroPie](https://retropie.org.uk/) is a frontend for emulators that allows you to turn your Raspberry Pi, ODroid C1/C2, or PC into a retro-gaming machine. It builds upon Raspbian, [EmulationStation](https://github.com/Aloshi/EmulationStation), RetroArch and many other projects to enable you to play your favourite Arcade, home-console, and classic PC games with the minimum set-up.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/153087555-e1bde100-6079-4089-a33d-804e29064789.png">
<br />
</p>

[RetroArch](https://www.retroarch.com/) is a frontend for emulators, game engines and media players. It enables you to run classic games on a wide range of computers and consoles through its slick graphical interface. Settings are also unified so configuration is done once and for all. [RetroArch Flatpak](https://flathub.org/apps/details/org.libretro.RetroArch)

[Dolphin](https://dolphin-emu.org) is an emulator for two recent Nintendo video game consoles: the GameCube and the Wii. It allows PC gamers to enjoy games for these two consoles in full HD (1080p) with several enhancements: compatibility with all PC controllers, turbo speed, networked multiplayer, and even more. [Dolphin Flatpak](https://flathub.org/apps/details/org.DolphinEmu.dolphin-emu)

[Citra](https://citra-emu.org/) is an open-source emulator for the Nintendo 3DS capable of playing many of your favorite games. [Citra Flatpak](https://flathub.org/apps/details/org.citra_emu.citra)

[yuzu](https://yuzu-emu.org) is an experimental open-source emulator for the Nintendo Switch from the creators of Citra.[Yuzu Flatpak](https://flathub.org/apps/details/org.yuzu_emu.yuzu)

[m64p](https://m64p.github.io/) is a Nintendo 64 Emulator. It uses mupen64plus-gui, a brand new mupen64plus frontend written in Qt5. It supports all of the things you’d expect from a frontend (savestate management, pausing, screenshots). [m64p Flatpak](https://flathub.org/apps/details/io.github.m64p.m64p)

[DeSmuME](https://desmume.org/) is a Nintendo DS emulator. [DeSmuME Flatpak](https://flathub.org/apps/details/org.desmume.DeSmuME)

[Snes9x](https://www.snes9x.com/) is a portable, freeware Super Nintendo Entertainment System (SNES) emulator. [Snes9x Flatpak](https://flathub.org/apps/details/com.snes9x.Snes9x) 

[bsnes](https://github.com/bsnes-emu/bsnes) is a Super Nintendo (SNES) emulator focused on performance, features, and ease of use. [bsnes flatpak](https://flathub.org/apps/details/dev.bsnes.bsnes)

[mGBA](https://mgba.io/) is a new emulator for running Game Boy Advance games. It aims to be faster and more accurate than many existing Game Boy Advance emulators, as well as adding features that other emulators lack. [mGBA Flatpak](https://flathub.org/apps/details/io.mgba.mGBA)

[DOSBox](https://www.dosbox.com/) is an open-source DOS emulator which primarily focuses on running DOS Games.

[DOSBox Staging](https://github.com/dosbox-staging/dosbox-staging) is a full x86 CPU emulator (independent of host architecture), capable of running DOS programs that require real or protected mode.[DOSBox Staging Flatpak](https://flathub.org/apps/details/io.github.dosbox-staging)

[Flycast](https://github.com/flyinghead/flycast) is a multi-platform Sega Dreamcast, Naomi and Atomiswave emulator derived from reicast. [Flycast Flatpak](https://flathub.org/apps/details/org.flycast.Flycast)

[PCSX2](https://pcsx2.net/) is a Playstation 2 'emulator', a free program that tries to replicate the Playstation 2 console to enable you to play PS2 games on your PC. [PCSX2 Flatpak](https://flathub.org/apps/details/net.pcsx2.PCSX2)

[RPCS3](https://rpcs3.net/) is an experimental open-source Sony PlayStation 3 emulator and debugger written in C++ for Windows and Linux. RPCS3 started development in May of 2011 by its founders DH and Hykem. The emulator is currently capable of running over 1800 commercial titles powered by Vulkan and OpenGL. [RPCS3 Flatpak](https://flathub.org/apps/details/net.rpcs3.RPCS3)

[MAME](https://www.mamedev.org/) is a Arcade Machine Emulator.

[xemu](https://xemu.app/) is an original Xbox emulator.

[Xenia](https://github.com/xenia-project/xenia) is an Xbox 360 Emulator.

**Also checkout these subreddits for more great Game Emulators recommendations**
  
   - [r/emulation](https://www.reddit.com/r/emulation/)
   - [r/emulations](https://www.reddit.com/r/emulators/)
   - [r/RetroArch](https://www.reddit.com/r/RetroArch/)
   - [r/RetroPie](https://www.reddit.com/r/RetroPie/)
   - [r/DolphinEmulator](https://www.reddit.com/r/DolphinEmulator/)
   - [r/Citra](https://www.reddit.com/r/Citra/)
   - [r/cemu](https://www.reddit.com/r/cemu/)
   - [r/yuzu](https://www.reddit.com/r/yuzu/)
   - [r/OpenEmu](https://www.reddit.com/r/OpenEmu/)
   - [r/MAME](https://www.reddit.com/r/MAME/)
   - [r/EmuDev](https://www.reddit.com/r/EmuDev/)
   - [r/Roms](https://www.reddit.com/r/Roms/)
 
## Wine

[WINE(Wine Is Not an Emulator)](https://www.winehq.org) is a compatibility layer capable of running Windows applications on several POSIX-compliant operating systems, such as Linux, macOS, & BSD. Instead of simulating internal Windows logic like a virtual machine or emulator, Wine translates Windows API calls into POSIX calls on-the-fly, eliminating the performance and memory penalties of other methods and allowing you to cleanly integrate Windows applications into your desktop.

## Winetricks

[Winetricks](https://github.com/Winetricks/winetricks) is an easy way to work around problems in Wine.

this is needed to avoid adobeair error
```sh
sudo sed -i 's|echo "\${arg%%=\*}"=\\""${arg### \*=}"\\"|echo \${arg%%=\*}=\\"\${arg### \*=}\\"|g' /usr/local/bin/winetricks
sudo apt install cabextract libncurses5:armhf
```

# Home Media Server

[Back to the Top](https://github.com/mikeroyal/Raspberry-Pi-Guide/blob/main/README.md#table-of-contents)

[Streaming Netflix, Amazon Prime, Hulu, HBO Go, Disney Plus, Spotify, Pandora and more on Raspberry Pi 4 with widevine](https://kirelos.com/raspberry-pi-os-gets-official-widevine-support-allowing-you-to-play-netflix-amazon-prime-hulu-etc/)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/112692924-f6849c80-8e3c-11eb-9311-0afdc14227f3.png">
</p>

[ReadyMedia (previously MiniDLNA)](https://wiki.archlinux.org/index.php/ReadyMedia) is server software with the aim of being fully compliant with DLNA / UPnP clients. The MiniDNLA daemon serves media files (music, pictures, and video) to clients on a network.

[Kodi (formerly XBMC)](https://kodi.tv/) is a free and open source media player and entertainment hub for digital media for HTPCs (Home theater PCs) application developed by the XBMC/Kodi Foundation. It uses a 10-foot user interface designed to be a media player for the living-room, using a remote control as the primary input device.

[Plex Media Server](https://www.plex.tv/) is an application that scans and organizes your media(music, videos, and other media files), then lets you stream it to all of your devices(computers, smartphones, tablets, televisions, streaming devices, and game consoles).

[OpenMediaVault](https://www.openmediavault.org/) is the next generation network attached storage (NAS) solution based on Debian Linux. It contains services like SSH, (S)FTP, SMB/CIFS, DAAP media server, RSync, BitTorrent client and many more.

[Mopidy](https://mopidy.com/) is a free and open source application that can turn your Raspberry Pi into music player for streaming local files, Spotify, Google Music, SoundCloud, Webradio, Podcasts and other music from the cloud. Also, stream your own collection from a device in your local network.

[Emby](https://emby.media/) is a media server designed to organize, play, and stream audio and video to a variety of devices(Android TV, Amazon Fire TV, Chromecast, Roku, Xbox, Home Theater Computers, and more). 

[Jellyfin](https://jellyfin.org/) is a volunteer-built media solution that puts you in control of your media. Stream to any device from your own server, with no strings attached. 

# WireGuard
[Back to the Top](https://github.com/mikeroyal/Raspberry-Pi-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/147891038-00f57362-e843-4bfb-be31-606c954d4e6c.png">
  <br />
</p>


[WireGuard®](https://www.wireguard.com/) is a straight-forward, fast and modern VPN that utilizes state-of-the-art cryptography. It aims to be faster, simpler, leaner, and more useful than IPsec while avoiding the massive headache. It intends to be considerably more performant than OpenVPN. WireGuard is designed as a general-purpose VPN for running on embedded interfaces and super computers alike, fit for many circumstances. Initially released for the Linux kernel, it is now cross-platform (Windows, macOS, BSD, iOS, Android) and widely deployable. It is currently under a massive development, but it already might be regarded as the most secure, most comfortable to use, and the simplest VPN solution in the industry.

[Wiretrustee](https://wiretrustee.com/) is a WireGuard®-based mesh network that connects your devices into a single private network.

[Wireguard Manager](https://github.com/complexorganizations/wireguard-manager) is a tool that enables you to build your own vpn under a minute.

[Tailscale](https://github.com/tailscale) is a WireGuard-based app that makes secure, private networks easy for teams of any scale. It works like an [overlay network](https://tailscale.com/blog/how-tailscale-works/) between the computers of your networks using all kinds of [NAT traversal sorcery](https://tailscale.com/blog/how-nat-traversal-works/).

[Headscale](https://github.com/juanfont/headscale) is an open source, self-hosted implementation of the Tailscale coordination server.

[BoringTun](https://github.com/cloudflare/boringtun) is an implementation of the WireGuard® protocol designed for portability and speed. It's successfully deployed on millions of [iOS](https://apps.apple.com/us/app/1-1-1-1-faster-internet/id1423538627) and [Android](https://play.google.com/store/apps/details?id=com.cloudflare.onedotonedotonedotone&hl=en_US) consumer devices as well as thousands of Cloudflare Linux servers.

[PiVPN](https://pivpn.io/) is the simplest VPN installer, designed for [Raspberry Pi](https://www.raspberrypi.com).

[Algo VPN](https://github.com/trailofbits/algo) is a set of Ansible scripts that simplify the setup of a personal WireGuard and IPsec VPN. It uses the most secure defaults available and works with common cloud providers.

[Pro Custodibus](https://www.procustodibus.com/features/) is a tool for managing WireGuard with a variety of business VPN (Virtual Private Network) use cases, such as site-to-site connectivity, secure remote access from anywhere, secure access to the cloud (Amazon Web Services, Google Cloud Platform, Microsoft Azure, etc), and more.

[Drago](https://seashell.github.io/drago) is a flexible configuration manager for WireGuard designed to make it simple to configure secure network overlays spanning heterogeneous nodes distributed across different clouds and physical locations. Drago is in active development, and we welcome contributions from the open-source community.

[Netmaker](https://netmaker.org/) is a tool that helps connect any computers together over a secure, fast, private network, and manage multiple networks from a central server.

[Kilo](https://github.com/squat/kilo) is a multi-cloud network overlay built on WireGuard and designed for Kubernetes. Kilo connects nodes in a cluster by providing an encrypted layer 3 network that can span across data centers and public clouds. The Pod network created by Kilo is always fully connected, even when the nodes are in different networks or behind NAT. By allowing pools of nodes in different locations to communicate securely, Kilo enables the operation of multi-cloud clusters. Kilo's design allows clients to VPN to a cluster in order to securely access services running on the cluster.

[Subspace](https://github.com/subspacecloud/subspace) is a simple WireGuard VPN server GUI.

[WG UI](https://github.com/EmbarkStudios/wg-ui) is a basic, self-contained management service for WireGuard with a self-serve web UI.

[WireHole](https://github.com/IAmStoxe/wirehole) is a combination of WireGuard, PiHole, and Unbound in a docker-compose project with the intent of enabling users to quickly and easily create and deploy a personally managed full or split-tunnel WireGuard VPN with ad blocking capabilities (via Pihole), and DNS caching with additional privacy options (via Unbound).

[Gluetun](https://github.com/qdm12/gluetun) is a lightwieght VPN client in a thin Docker container for multiple VPN providers, written in Go, and uses OpenVPN or Wireguard, DNS over TLS, with a few proxy servers built-in.

[Ethr](https://github.com/microsoft/ethr) is a cross platform network performance measurement tool written in golang. The goal of this project is to provide a native tool for comprehensive network performance measurements of bandwidth, connections/s, packets/s, latency, loss & jitter, across multiple protocols such as TCP, UDP, HTTP, HTTPS, and across multiple platforms such as Windows, Linux and other Unix systems.

# Nextcloud
[Back to the Top](https://github.com/mikeroyal/Raspberry-Pi-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/150701955-f1f514a8-82e6-462f-9fc9-8926b6b7de3e.png">
  <br />
  
</p>

[Nextcloud](https://nextcloud.com) is an industry-leading, on-premises content collaboration platform for file sync & share and communication server. It is fully open source and you can host it yourself or pay a company to do it for you. Also checkout the following links below:

   - [Nextcloud App Store](https://apps.nextcloud.com)

   - [Nextcloud GitHub](https://github.com/nextcloud)

   - [Nextcloud Developer Program](https://nextcloud.com/developer)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/150701961-ac8be115-34c1-4012-bd69-d1f22a10e48c.png">
  <br />
Nexcloud login screen
</p>

[Nextcloud Hub](https://nextcloud.com/hub/) is a tool that allows you to share and collaborate on documents, send and receive email, manage your calendar and have video chats without data leaks. As fully on-premises solution, Nextcloud Hub provides the benefits of online collaboration without the compliance and security risks.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/150701964-df1dd8d9-1d3a-4376-81e8-f49439fb4356.png">
  <br />
Nexcloud Hub
</p>

[Nextcloud Desktop Client](https://nextcloud.com/install/#install-clients) is a tool to synchronize files from Nextcloud Server with your computer.

[Nextcloud Deck](https://apps.nextcloud.com/apps/deck) is a kanban style organization tool aimed at personal planning and project organization for teams integrated with Nextcloud.

[Nextcloud Files](https://nextcloud.com/files/) is a tool tool that allows your employees have easy access to their files, photos and documents to work and can share and collaborate with team members, customers and partners. So IT knows nobody besides those they shared with has access to those files.

[Nextcloud Talk](https://nextcloud.com/talk/) is a tool that protects your communication better than other team collaboration platforms like Microsoft Teams or Slack, making sure your data stays on your servers. It also goes further than other encrypted communication technologies by keeping even metadata from leaking.

[Nextcloud Home](https://nextcloud.com/athome/) is a tool that allows you store your documents, calendar, contacts and photos on your server at home, at one of at one Nextcloud's providers or in a data center you trust.

[Nextcloud Enterprise](https://nextcloud.com/enterprise/) is a service that gives professional organizations software optimized and tested for mission critical environments.

[Nextcloud Outlook Integration](https://nextcloud.com/outlook/) is a tool that automatically upload files to replace large attachments or integrate Calendars and Contacts in Microsoft Outlook.

[Collabora Online in Nextcloud](https://nextcloud.com/collaboraonline/) is a powerful LibreOffice-based online office suite with collaborative editing, which supports all major document, spreadsheet and presentation file formats and works in all modern browsers.

[ONLYOFFICE integration in Nextcloud](https://nextcloud.com/onlyoffice/) is a service that empowers your users to collaborate on office documents with team members in real time. It has compatibility with Microsoft Office formats means perfect documents, every time.

[Nextcloud VM(virtual machine appliance)](https://download.nextcloudvm.com/) is a set of carefully crafted family of [*nix](https://bit.ly/2UaCC7b) scripts, which interactively guide you through a quality-controlled installation of a Nextcloud instance for Home/SME Server and scripts for Raspberry Pi 4. It is Community developed and maintained.

# Grafana
[Back to the Top](https://github.com/mikeroyal/Raspberry-Pi-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398126-eea08800-dcc8-11eb-8129-087e924d9eed.png">
  <br />
</p>

## Grafana Learning Resources

[Grafana](https://grafana.com/) is an analytics platform that enables you to query and visualize data, then create and share dashboards based on your visualizations. Easily visualize metrics, logs, and traces from multiple sources such as Prometheus, Loki, Elasticsearch, InfluxDB, Postgres, Fluentd, Fluentbit, Logstash and many more.

[Getting Started with Grafana](https://grafana.com/docs/)

[Grafana Community](https://community.grafana.com/)

[Grafana Professional Services Training | Grafana Labs](https://grafana.com/training/)

[Grafana Pro Training AWS | Grafana Labs](https://grafana.com/training/aws/)

[Grafana Tutorials](https://grafana.com/tutorials/)

[Top Grafana Courses on Udemy](https://www.udemy.com/topic/grafana/)

[Grafana Online Training Courses | LinkedIn Learning](https://www.linkedin.com/learning/topics/grafana)

[Grafana Training Courses - NobleProg](https://www.nobleprog.com/grafana-training)

[Setting Up Grafana to Visualize Our Metrics Course on Coursera](https://www.coursera.org/lecture/continuous-integration/setting-up-grafana-to-visualize-our-metrics-part-4-of-10-OOMzF)

## Grafana Tools

[Grafana Cloud ](https://grafana.com/products/cloud/) is a composable observability platform, integrating metrics, traces and logs with Grafana. Leverage the best open source observability software – including Prometheus, Loki, and Tempo – without the overhead of installing, maintaining, and scaling your observability stack.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398133-f3653c00-dcc8-11eb-8465-8633072daf41.png">
  <br />
</p>

**Grafana Cloud Integrations. Source: [Grafana](https://grafana.com/products/cloud/)**

[Grafana Enterprise](https://grafana.com/products/enterprise/) is a service that includes features that provide better scalability, collaboration, operations, and governance in a self-managed environment.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/124398134-f4966900-dcc8-11eb-8633-448074c93f71.png">
  <br />
</p>

**Grafana Enterprise Stack. Source: [Grafana](https://grafana.com/products/enterprise/)**

[Grafana Tempo](https://grafana.com/oss/tempo/) is an open source high-scale distributed tarcing backend. Tempo is cost-efficient, requiring only object storage to operate, and is deeply integrated with Grafana, Loki, and Prometheus.

[Grafana MetricTank](https://grafana.com/oss/metrictank/) is a multi-tenant timeseries platform for Graphite developed by Grafana Labs. MetricTank provides high-availability(HA) and efficient long-term storage, retrieval, and processing for large-scale environments.

[Grafana Tanka](https://grafana.com/oss/tanka/) is a robust configuration utility for your [Kubernetes](https://kubernetes.io/) cluster, powered by the [Jsonnet](https://jsonnet.org/) language.

[Grafana Loki](https://grafana.com/oss/loki/) is a horizontally-scalable, highly-available(HA), multi-tenant log aggregation system inspired by Prometheus.

[Cortex](https://grafana.com/oss/cortex/) is a project that lets users query metrics from many Prometheusservers in a single place, without any gaps in the grpahs due to server failture. Also, Cortex lets you store Prometheus metrics for long term capacity planning and performance analysis.

[Graphite](https://grafana.com/oss/graphite/) is an open source monitoring system.

# Kubernetes

[Back to the Top](https://github.com/mikeroyal/Raspberry-Pi-Guide/blob/main/README.md#table-of-contents)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/95383873-a884d800-08a0-11eb-8eaf-57af5b119f56.png">
</p>

**Note: The recommended hardware is the Raspberry Pi 4 Model B with 8 GB of Memory**

[Kubernetes (K8s)](https://kubernetes.io/) is an open-source system for automating deployment, scaling, and management of containerized applications. 

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/105645195-db9ea780-5e4e-11eb-8357-fb38b2f06d74.png">

**Building Highly-Availability(HA) Clusters with kubeadm. Source: [Kubernetes.io](https://kubernetes.io/docs/setup/production-environment/tools/kubeadm/high-availability/), 2020**
</p>

[Google Kubernetes Engine (GKE)](https://cloud.google.com/kubernetes-engine/) is a managed, production-ready environment for running containerized applications.

[Azure Kubernetes Service (AKS)](https://azure.microsoft.com/en-us/services/kubernetes-service/) is serverless Kubernetes, with a integrated continuous integration and continuous delivery (CI/CD) experience, and enterprise-grade security and governance. Unite your development and operations teams on a single platform to rapidly build, deliver, and scale applications with confidence.

[Amazon EKS](https://docs.aws.amazon.com/eks/latest/userguide/what-is-eks.html) is a tool that runs Kubernetes control plane instances across multiple Availability Zones to ensure high availability.

[AWS Controllers for Kubernetes (ACK)](https://aws.amazon.com/blogs/containers/aws-controllers-for-kubernetes-ack/) is a new tool that lets you directly manage AWS services from Kubernetes. ACK makes it simple to build scalable and highly-available Kubernetes applications that utilize AWS services.

[Container Engine for Kubernetes (OKE)](https://www.oracle.com/cloud-native/container-engine-kubernetes/) is an Oracle-managed container orchestration service that can reduce the time and cost to build modern cloud native applications. Unlike most other vendors, Oracle Cloud Infrastructure provides Container Engine for Kubernetes as a free service that runs on higher-performance, lower-cost compute.

[Anthos](https://cloud.google.com/anthos/docs/concepts/overview) is a modern application management platform that provides a consistent development and operations experience for cloud and on-premises environments.

[Red Hat Openshift](https://www.openshift.com/) is a fully managed Kubernetes platform that provides a foundation for on-premises, hybrid, and multicloud deployments. 

[OKD](https://okd.io/) is a community distribution of Kubernetes optimized for continuous application development and multi-tenant deployment. OKD adds developer and operations-centric tools on top of Kubernetes to enable rapid application development, easy deployment and scaling, and long-term lifecycle maintenance for small and large teams.

[Odo](https://odo.dev/) is a fast, iterative, and straightforward CLI tool for developers who write, build, and deploy applications on Kubernetes and OpenShift.

[Kata Operator](https://github.com/openshift/kata-operator) is an operator to perform lifecycle management (install/upgrade/uninstall) of [Kata Runtime](https://katacontainers.io/) on Openshift as well as Kubernetes cluster.

[Thanos](https://thanos.io/) is a set of components that can be composed into a highly available metric system with unlimited storage capacity, which can be added seamlessly on top of existing Prometheus deployments.

[OpenShift Hive](https://github.com/openshift/hive) is an operator which runs as a service on top of Kubernetes/OpenShift. The Hive service can be used to provision and perform initial configuration of OpenShift 4 clusters.

[Rook](https://rook.io/) is a tool that turns distributed storage systems into self-managing, self-scaling, self-healing storage services. It automates the tasks of a storage administrator: deployment, bootstrapping, configuration, provisioning, scaling, upgrading, migration, disaster recovery, monitoring, and resource management.

[VMware Tanzu](https://tanzu.vmware.com/tanzu) is a centralized management platform for consistently operating and securing your Kubernetes infrastructure and modern applications across multiple teams and private/public clouds.

[Kubespray](https://kubespray.io/) is a tool that combines Kubernetes and Ansible to easily install Kubernetes clusters that can be deployed on [AWS](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/aws.md), GCE, [Azure](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/azure.md), [OpenStack](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/openstack.md), [vSphere](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/vsphere.md), [Packet](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/packet.md) (bare metal), Oracle Cloud Infrastructure (Experimental), or Baremetal.

[KubeInit](https://github.com/kubeinit/kubeinit) provides Ansible playbooks and roles for the deployment and configuration of multiple Kubernetes distributions.

[Rancher](https://rancher.com/) is a complete software stack for teams adopting containers. It addresses the operational and security challenges of managing multiple Kubernetes clusters, while providing DevOps teams with integrated tools for running containerized workloads.

[K3s](https://github.com/rancher/k3s) is a highly available, certified Kubernetes distribution designed for production workloads in unattended, resource-constrained, remote locations or inside IoT appliances. 

[Helm](https://helm.sh/) is a Kubernetes Package Manager tool that makes it easier to install and manage Kubernetes applications.

[Knative](https://knative.dev/) is a Kubernetes-based platform to build, deploy, and manage modern serverless workloads. Knative takes care of the operational overhead details of networking, autoscaling (even to zero), and revision tracking. 

[KubeFlow](https://www.kubeflow.org/) is a tool dedicated to making deployments of machine learning (ML) workflows on Kubernetes simple, portable and scalable.

[Etcd](https://etcd.io/) is a distributed key-value store that provides a reliable way to store data that needs to be accessed by a distributed system or cluster of machines. Etcd is used as the backend for service discovery and stores cluster state and configuration for Kubernetes.

[OpenEBS](https://openebs.io/) is a Kubernetes-based tool to create stateful applications using Container Attached Storage.

[Container Storage Interface (CSI)](https://www.architecting.it/blog/container-storage-interface/) is an API that lets container orchestration platforms like Kubernetes seamlessly communicate with stored data via a plug-in.

[MicroK8s](https://microk8s.io/) is a tool that delivers the full Kubernetes experience. In a Fully containerized deployment with compressed over-the-air updates for ultra-reliable operations. It is supported on Linux, Windows, and MacOS.

[Charmed Kubernetes](https://ubuntu.com/kubernetes/features) is a well integrated, turn-key, conformant Kubernetes platform, optimized for your multi-cloud environments developed by Canonical.

[Grafana Kubernetes App](https://grafana.com/grafana/plugins/grafana-kubernetes-app) is a toll that allows you to monitor your Kubernetes cluster's performance. It includes 4 dashboards, Cluster, Node, Pod/Container and Deployment. It allows for the automatic deployment of the required Prometheus exporters and a default scrape config to use with your in cluster Prometheus deployment.

[KubeEdge](https://kubeedge.io/en/) is an open source system for extending native containerized application orchestration capabilities to hosts at Edge.It is built upon kubernetes and provides fundamental infrastructure support for network, app. deployment and metadata synchronization between cloud and edge.

[Lens](https://k8slens.dev/)  is the most powerful IDE for people who need to deal with Kubernetes clusters on a daily basis. It has support for MacOS, Windows and Linux operating systems.

[kind](https://kind.sigs.k8s.io/) is a tool for running local Kubernetes clusters using Docker container “nodes”. It was primarily designed for testing Kubernetes itself, but may be used for local development or CI.

[Flux CD](https://fluxcd.io/) is a tool that automatically ensures that the state of your Kubernetes cluster matches the configuration you've supplied in Git. It uses an operator in the cluster to trigger deployments inside Kubernetes, which means that you don't need a separate continuous delivery tool.

## Kubernetes Learning Resources

[Getting Kubernetes Certifications](https://training.linuxfoundation.org/certification/catalog/?_sft_technology=kubernetes)

[Getting started with Kubernetes on AWS](https://aws.amazon.com/kubernetes/)

[Kubernetes on Microsoft Azure](https://azure.microsoft.com/en-us/topic/what-is-kubernetes/)

[Intro to Azure Kubernetes Service](https://docs.microsoft.com/en-us/azure/aks/kubernetes-dashboard)

[Getting started with Google Cloud](https://cloud.google.com/learn/what-is-kubernetes)

[Getting started with Kubernetes on Red Hat](https://www.redhat.com/en/topics/containers/what-is-kubernetes)

[Getting started with Kubernetes on IBM](https://www.ibm.com/cloud/learn/kubernetes)

[YAML basics in Kubernetes](https://developer.ibm.com/technologies/containers/tutorials/yaml-basics-and-usage-in-kubernetes/)

[Elastic Cloud on Kubernetes](https://www.elastic.co/elastic-cloud-kubernetes)

[Docker and Kubernetes](https://www.docker.com/products/kubernetes)

[Deploy a model to an Azure Kubernetes Service cluster](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-deploy-azure-kubernetes-service?tabs=python)

[Simplify Machine Learning Inference on Kubernetes with Amazon SageMaker Operators](https://aws.amazon.com/blogs/machine-learning/simplify-machine-learning-inference-on-kubernetes-with-amazon-sagemaker-operators/)

[Running Apache Spark on Kubernetes](http://spark.apache.org/docs/latest/running-on-kubernetes.html)

[Kubernetes Across VMware vRealize Automation](https://blogs.vmware.com/management/2019/06/kubernetes-across-vmware-cloud-automation-services.html)

[VMware Tanzu Kubernetes Grid](https://tanzu.vmware.com/kubernetes-grid)

[All the Ways VMware Tanzu Works with AWS](https://tanzu.vmware.com/content/blog/all-the-ways-vmware-tanzutm-works-with-aws)

[VMware Tanzu Education](https://tanzu.vmware.com/education)

[Using Ansible in a Cloud-Native Kubernetes Environment](https://www.ansible.com/blog/how-useful-is-ansible-in-a-cloud-native-kubernetes-environment)

[Managing Kubernetes (K8s) objects with Ansible](https://docs.ansible.com/ansible/latest/collections/community/kubernetes/k8s_module.html)

[Setting up a Kubernetes cluster using Vagrant and Ansible](https://kubernetes.io/blog/2019/03/15/kubernetes-setup-using-ansible-and-vagrant/)

[Running MongoDB with Kubernetes](https://www.mongodb.com/kubernetes)

[Kubernetes Fluentd](https://docs.fluentd.org/v/0.12/articles/kubernetes-fluentd)

[Understanding the new GitLab Kubernetes Agent](https://about.gitlab.com/blog/2020/09/22/introducing-the-gitlab-kubernetes-agent/)

[Kubernetes Contributors](https://www.kubernetes.dev/)

[KubeAcademy from VMware](https://kube.academy/)

# Machine Learning

[Back to the Top](https://github.com/mikeroyal/Raspberry-Pi-Guide/blob/main/README.md#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/108111395-756e0480-7049-11eb-85ca-b87315e9d3ef.jpeg">
 </p>
 
 **Note: The recommended hardware is the Raspberry Pi 4 Model B with 8 GB of Memory**
 
 ## ML frameworks & applications

[TensorFlow Lite](https://www.tensorflow.org/lite/guide) is a set of tools to help developers run TensorFlow models on mobile, embedded, and IoT devices. It enables on-device machine learning inference with low latency and a small binary size.

[PyTorch](https://pytorch.org) is a library for deep learning on irregular input data such as graphs, point clouds, and manifolds. Primarily developed by Facebook's AI Research lab.

[Amazon SageMaker](https://aws.amazon.com/sagemaker/) is a fully managed service that provides every developer and data scientist with the ability to build, train, and deploy machine learning (ML) models quickly. SageMaker removes the heavy lifting from each step of the machine learning process to make it easier to develop high quality models.

[Azure Databricks](https://azure.microsoft.com/en-us/services/databricks/) is a fast and collaborative Apache Spark-based big data analytics service designed for data science and data engineering. Azure Databricks, sets up your Apache Spark environment in minutes, autoscale, and collaborate on shared projects in an interactive workspace. Azure Databricks supports Python, Scala, R, Java, and SQL, as well as data science frameworks and libraries including TensorFlow, PyTorch, and scikit-learn.

[Microsoft Cognitive Toolkit (CNTK)](https://docs.microsoft.com/en-us/cognitive-toolkit/) is an open-source toolkit for commercial-grade distributed deep learning. It describes neural networks as a series of computational steps via a directed graph. CNTK allows the user to easily realize and combine popular model types such as feed-forward DNNs, convolutional neural networks (CNNs) and recurrent neural networks (RNNs/LSTMs). CNTK implements stochastic gradient descent (SGD, error backpropagation) learning with automatic differentiation and parallelization across multiple GPUs and servers.

[Apache Airflow](https://airflow.apache.org) is an open-source workflow management platform created by the community to programmatically author, schedule and monitor workflows. Install. Principles. Scalable. Airflow has a modular architecture and uses a message queue to orchestrate an arbitrary number of workers. Airflow is ready to scale to infinity.

[Open Neural Network Exchange(ONNX)](https://github.com/onnx) is an open ecosystem that empowers AI developers to choose the right tools as their project evolves. ONNX provides an open source format for AI models, both deep learning and traditional ML. It defines an extensible computation graph model, as well as definitions of built-in operators and standard data types.

[Apache MXNet](https://mxnet.apache.org/) is a deep learning framework designed for both efficiency and flexibility. It allows you to mix symbolic and imperative programming to maximize efficiency and productivity. At its core, MXNet contains a dynamic dependency scheduler that automatically parallelizes both symbolic and imperative operations on the fly. A graph optimization layer on top of that makes symbolic execution fast and memory efficient. MXNet is portable and lightweight, scaling effectively to multiple GPUs and multiple machines. Support for Python, R, Julia, Scala, Go, Javascript and more.

[AutoGluon](https://autogluon.mxnet.io/index.html) is toolkit for Deep learning that automates machine learning tasks enabling you to easily achieve strong predictive performance in your applications. With just a few lines of code, you can train and deploy high-accuracy deep learning models on tabular, image, and text data.

[Anaconda](https://www.anaconda.com/) is a very popular Data Science platform for machine learning and deep learning that enables users to develop models, train them, and deploy them.

[PlaidML](https://github.com/plaidml/plaidml) is an advanced and portable tensor compiler for enabling deep learning on laptops, embedded devices, or other devices where the available computing hardware is not well supported or the available software stack contains unpalatable license restrictions.

[OpenCV](https://opencv.org) is a highly optimized library with focus on real-time computer vision applications. The C++, Python, and Java interfaces support Linux, MacOS, Windows, iOS, and Android.

[Scikit-Learn](https://scikit-learn.org/stable/index.html) is a Python module for machine learning built on top of SciPy, NumPy, and matplotlib, making it easier to apply robust and simple implementations of many popular machine learning algorithms.

[Weka](https://www.cs.waikato.ac.nz/ml/weka/) is an open source machine learning software that can be accessed through a graphical user interface, standard terminal applications, or a Java API. It is widely used for teaching, research, and industrial applications, contains a plethora of built-in tools for standard machine learning tasks, and additionally gives transparent access to well-known toolboxes such as scikit-learn, R, and Deeplearning4j. 

[Theano](https://github.com/Theano/Theano) is a Python library that allows you to define, optimize, and evaluate mathematical expressions involving multi-dimensional arrays efficiently including tight integration with NumPy.

[nGraph](https://github.com/NervanaSystems/ngraph) is an open source C++ library, compiler and runtime for Deep Learning. The nGraph Compiler aims to accelerate developing AI workloads using any deep learning framework and deploying to a variety of hardware targets.It provides the freedom, performance, and ease-of-use to AI developers.

[Jupyter Notebook](https://jupyter.org/) is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text. Jupyter is used widely in industries that do data cleaning and transformation, numerical simulation, statistical modeling, data visualization, data science, and machine learning.

## Online ML Learning Resources

[Machine Learning by Stanford University from Coursera](https://www.coursera.org/learn/machine-learning)

[Machine Learning Courses Online from Coursera](https://www.coursera.org/courses?query=machine%20learning&)

[Machine Learning Courses Online from Udemy](https://www.udemy.com/topic/machine-learning/)

[Learn Machine Learning with Online Courses and Classes from edX](https://www.edx.org/learn/machine-learning)

# Robotics

[Back to the Top](https://github.com/mikeroyal/Raspberry-Pi-Guide/blob/main/README.md#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/96352533-b55fb380-1078-11eb-874c-f165cbcce899.png">
</p>

## Tools for Robotics

[ROS](https://www.ros.org/) is robotics middleware. Although ROS is not an operating system, it provides services designed for a heterogeneous computer cluster such as hardware abstraction, low-level device control, implementation of commonly used functionality, message-passing between processes, and package management.

[ROS2](https://index.ros.org/doc/ros2/) is a set of [software libraries and tools](https://github.com/ros2) that help you build robot applications. From drivers to state-of-the-art algorithms, and with powerful developer tools, ROS has what you need for your next robotics project. And it’s all open source.

[Robot Framework](https://robotframework.org/) is a generic open source automation framework. It can be used for test automation and robotic process automation. It has easy syntax, utilizing human-readable keywords. Its capabilities can be extended by libraries implemented with Python or Java. 

[The Robotics Library (RL)](https://github.com/roboticslibrary/rl) is a self-contained C++ library for robot kinematics, motion planning and control. It covers mathematics, kinematics and dynamics, hardware abstraction, motion planning, collision detection, and visualization.RL runs on many different systems, including Linux, macOS, and Windows. It uses CMake as a build system and can be compiled with Clang, GCC, and Visual Studio.

[MoveIt](https://moveit.ros.org/) is the most widely used software for manipulation and has been used on over 100 robots. It provides an easy-to-use robotics platform for developing advanced applications, evaluating new designs and building integrated products for industrial, commercial, R&D, and other domains.

[AutoGluon](https://autogluon.mxnet.io/index.html) is toolkit for [Deep learning](https://gitlab.com/maos20008/intro-to-machine-learning) that automates machine learning tasks enabling you to easily achieve strong predictive performance in your applications. With just a few lines of code, you can train and deploy high-accuracy deep learning models on tabular, image, and text data.

[Gazebo](http://gazebosim.org/) accurately and efficiently simulates indoor and outdoor robots. You get a robust physics engine, high-quality graphics, and programmatic and graphical interfaces.

[Robotics System Toolbox](https://www.mathworks.com/products/robotics.html) provides tools and algorithms for designing, simulating, and testing manipulators, mobile robots, and humanoid robots. For manipulators and humanoid robots, the toolbox includes algorithms for collision checking, trajectory generation, forward and inverse kinematics, and dynamics using a rigid body tree representation. 
For mobile robots, it includes algorithms for mapping, localization, path planning, path following, and motion control. The toolbox provides reference examples of common industrial robot applications. It also includes a library of 
commercially available industrial robot models that you can import, visualize, and simulate.

[Intel Robot DevKit](https://github.com/intel/robot_devkit) is the tool to generate Robotics Software Development Kit (RDK) designed for autonomous devices, including the ROS2 core and capacibilities packages like perception, planning, control driver etc. It provides flexible build/runtime configurations to meet different autonomous requirement on top of diversity hardware choices, for example use different hareware engine CPU/GPU/VPU to accelerate AI related features.

[Arduino](https://www.arduino.cc/) is an open-source platform used for building electronics projects. Arduino consists of both a physical programmable circuit board (often referred to as a microcontroller) and a piece of software, or IDE (Integrated Development Environment) that runs on your computer, used to write and upload computer code to the physical board.

[ArduPilot](https://ardupilot.org/ardupilot/index.html) enables the creation and use of trusted, autonomous, unmanned vehicle systems for the peaceful benefit of all. ArduPilot provides a comprehensive suite of tools suitable for almost any vehicle and application.

[AirSim](https://github.com/Microsoft/AirSim) is a simulator for drones, cars and more, built on Unreal Engine (we now also have an experimental Unity release). It is open-source, cross platform, and supports hardware-in-loop with popular flight controllers such as PX4 for physically and visually realistic simulations.

[F´ (F Prime)](https://github.com/nasa/fprime) is a component-driven framework that enables rapid development and deployment of spaceflight and other embedded software applications. Originally developed at the Jet Propulsion Laboratory, F´ has been successfully deployed on several space applications.

[The JPL Open Source Rover](https://github.com/nasa-jpl/open-source-rover) is an open source, build it yourself, scaled down version of the 6 wheel rover design that JPL uses to explore the surface of Mars. The Open Source Rover is designed almost entirely out of consumer off the shelf (COTS) parts. This project is intended to be a teaching and learning experience for those who want to get involved in mechanical engineering, software, electronics, or robotics.

[Light Detection and Ranging(LiDAR)](https://en.wikipedia.org/wiki/Lidar) is a remote sensing method that uses light in the form of a pulsed laser at an object, and uses the time and wavelength of the reflected beam of light to estimate the distance and in some applications ([Laser Imaging](https://en.wikipedia.org/wiki/Laser_scanning)), to create a 3D representation of the object and its surface characteristics. This technology is commonly used in aircraft and self-driving vehicles.

[AliceVision](https://github.com/alicevision/AliceVision) is a Photogrammetric Computer Vision Framework which provides a 3D Reconstruction and Camera Tracking algorithms. AliceVision aims to provide strong software basis with state-of-the-art computer vision algorithms that can be tested, analyzed and reused. The project is a result of collaboration between academia and industry to provide cutting-edge algorithms with the robustness and the quality required for production usage.

[CARLA](https://github.com/carla-simulator/carla) is an open-source simulator for autonomous driving research. CARLA has been developed from the ground up to support development, training, and validation of autonomous driving systems. In addition to open-source code and protocols, CARLA provides open digital assets (urban layouts, buildings, vehicles) that were created for this purpose and can be used freely. The simulation platform supports flexible specification of sensor suites and environmental conditions.

[ROS bridge](https://github.com/carla-simulator/ros-bridge) is a package to bridge ROS for CARLA Simulator.

[ROS-Industrial](https://rosindustrial.org/) is an open source project that extends the advanced capabilities of ROS software to manufacturing.

[AWS RoboMaker](https://aws.amazon.com/robomaker/) is the most complete cloud solution for robotic developers to simulate, test and securely deploy robotic applications at scale. RoboMaker provides a fully-managed, scalable infrastructure for simulation that customers use for multi-robot simulation and CI/CD integration with regression testing in simulation.

[Microsoft Robotics Developer Studio](https://www.microsoft.com/en-us/download/details.aspx?id=29081)  is a free .NET-based programming environment for building robotics applications. 

[Visual Studio Code Extension for ROS](https://github.com/ms-iot/vscode-ros) is an extension provides support for Robot Operating System (ROS) development.

[Azure Kinect ROS Driver](https://github.com/microsoft/azure_kinect_ros_driver) is a node which publishes sensor data from the [Azure Kinect Developer Kit](https://azure.microsoft.com/en-us/services/kinect-dk/) to the [Robot Operating System (ROS)](http://www.ros.org/). Developers working with ROS can use this node to connect an Azure Kinect Developer Kit to an existing ROS installation.

[Azure IoT Hub for ROS](https://github.com/microsoft/ros_azure_iothub) is a ROS package works with the Microsoft Azure IoT Hub service to relay telemetry messages from the Robot to Azure IoT Hub or reflect properties from the Digital Twin to the robot using dynamic reconfigure.

[ROS 2 with ONNX Runtime](https://github.com/ms-iot/ros_msft_onnx) is a program that uses ROS 2 to run on different hardware platforms using their respective AI acceleration libraries for optimized execution of the ONNX model.

[Azure Cognitive Services LUIS ROS Node](https://github.com/ms-iot/ros_msft_luis) is a ROS node that bridges between ROS and the Azure Language Understanding Service. it can be configured to process audio directly from a microphone, or can subscribe to a ROS audio topic, then processes speech and generates "intent" ROS messages which can be processed by another ROS node to generate ROS commands. 

## Robotics Learning Resources

[Robotics courses from Coursera](https://www.edx.org/learn/robotics)

[Learn Robotics with Online Courses and Classes from edX](https://www.edx.org/learn/robotics)

[Top Robotics Courses Online from Udemy](https://www.udemy.com/topic/robotics/)

[Free Online AI & Robotics Courses](https://www.futurelearn.com/subjects/it-and-computer-science-courses/ai-and-robotics)

[REC Foundation Robotics Industry Certification](https://www.roboticseducation.org/industry-certifications/)

[Carnegie Mellon Robotics Academy](https://www.cmu.edu/roboticsacademy/Training/Certifications.html)

[RIA Robotic Integrator Certification Program](https://www.robotics.org/robotics/integrator-certification)

[AWS RoboMaker – Develop, Test, Deploy, and Manage Intelligent Robotics Apps](https://aws.amazon.com/blogs/aws/aws-robomaker-develop-test-deploy-and-manage-intelligent-robotics-apps/)

# Node.js Development

[Back to the Top](https://github.com/mikeroyal/Raspberry-Pi-Guide/blob/main/README.md#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/93719688-0becd700-fb39-11ea-9b87-3d52f1828aee.png">
  <br />
</p>

## Node.js Learning Resources

[Node.js](https://nodejs.org/) is a JavaScript runtime built on Chrome's V8 JavaScript engine that lets developers write command line tools and server-side scripts outside of a browser.

[Node.js Build Working Group](https://github.com/nodejs/build) maintains and controls infrastructure used for continuous integration (CI), releases, benchmarks, web hosting (of nodejs.org and other Node.js web properties) and more.

[The OpenJS Foundation](https://openjsf.org/) is made up of 32 open source JavaScript projects including Appium, Dojo, Electron, jQuery, Node.js, and webpack. The foundation's mission is to support the healthy growth of JavaScript and web technologies by providing a neutral organization to host and sustain projects, as well as collaboratively fund activities that benefit the ecosystem as a whole.

[Set up NodeJS on WSL 2](https://docs.microsoft.com/en-us/windows/nodejs/setup-on-wsl2)

[Getting started with Node.js in Google Cloud](https://cloud.google.com/nodejs/getting-started)

[Getting Started with Node.js in AWS](https://docs.aws.amazon.com/sdk-for-javascript/v2/developer-guide/getting-started-nodejs.html)

[Node.js App Hosting & Deployment in Microsoft Azure](https://azure.microsoft.com/en-us/develop/nodejs/)

[The Node.js best practices list ](https://github.com/goldbergyoni/nodebestpractices)

[Introduction to Node.js by W3Schools](https://www.w3schools.com/nodejs/nodejs_intro.asp)

[The Node.js Community Committee](https://github.com/nodejs/community-committee)

[Node.js Mentorship Program Initiative](https://github.com/nodejs/mentorship)

[Node.js tutorial in Visual Studio Code](https://code.visualstudio.com/docs/nodejs/nodejs-tutorial)

[Server-side Development with NodeJS, Express and MongoDB on Coursera](https://www.coursera.org/learn/server-side-nodejs)

## Node.js Tools

[NPM](https://www.npmjs.com/) is the company behind Node package manager, the npm Registry, and npm CLI. 

[node-gyp](https://github.com/nodejs/node-gyp) is a cross-platform command-line tool written in Node.js for compiling native addon modules for Node.js. It contains a vendored copy of the gyp-next project that was previously used by the Chromium team, extended to support the development of Node.js native addons.

[nvm ](https://github.com/nvm-sh/nvm) is a version manager for node.js, designed to be installed per-user, and invoked per-shell. nvm works on any POSIX-compliant shell (sh, dash, ksh, zsh, bash), in particular on these platforms: unix, macOS, and windows WSL.

[node-docker](https://hub.docker.com/_/node/) is the official Node.js docker image, made with love by the node community.

[Mocha](https://github.com/mochajs/mocha) is a simple, flexible, fun JavaScript test framework for Node.js & The Browser.

[AVA](https://github.com/avajs/ava) is a test runner for Node.js with a concise API, detailed error output, embrace of new language features and process isolation that lets you develop with confidence.

[egg](https://eggjs.org/) is a born to build better enterprise frameworks and apps with Node.js & Koa.

[mysqljs](https://github.com/mysqljs/mysql) is a pure node.js JavaScript Client implementing the MySQL protocol. 

[axios](https://github.com/axios/axios) is a promise based HTTP client for the browser and node.js.

[Fastify](https://www.fastify.io/) is a fast and low overhead web framework, for Node.js. 

[Express](https://expressjs.com/) is a fast, unopinionated, minimalist web framework for node.

[Meteor](https://www.meteor.com/) is an ultra-simple environment for building modern web applications with JavavScript. 

[NW.js](https://nwjs.io/) is an app runtime based on Chromium and node.js. You can write native apps in HTML and JavaScript with NW.js. It also lets you call Node.js modules directly from the DOM and enables a new way of writing native applications with all Web technologies.

[PM2](https://pm2.io/) is a production process manager for Node.js applications with a built-in load balancer. It allows you to keep applications alive forever, to reload them without downtime and to facilitate common system admin tasks.

[NestJS](https://nestjs.com/) is a framework for building efficient, scalable Node.js web applications. It uses modern JavaScript, is built with TypeScript and combines elements of OOP (Object Oriented Progamming), FP (Functional Programming), and FRP (Functional Reactive Programming).

[jenkins-nodejs](https://plugins.jenkins.io/nodejs/) is a Jenkins plugin for Node.js that provides the NodeJS auto-installer, allowing to create as many NodeJS installations "profiles" as you want.

[Strapi](https://strapi.io/) is an open source Node.js Headless CMS to easily build customisable APIs. 

[Standard](https://standardjs.com/) is a JavaScript Style Guide, with linter & automatic code fixer.

[React Starter Kit](https://www.reactstarterkit.com/) is an isomorphic web app boilerplate for web development built on top of [Node.js](https://nodejs.org/), [Express](http://expressjs.com/), [GraphQL](http://graphql.org/) and [React](https://facebook.github.io/react/), containing modern web development tools such as [Webpack](https://webpack.github.io/), [Babel](https://babeljs.io/) and [Browsersync](https://www.browsersync.io/). Helping you to stay productive following the best practices.

[Hexo](https://hexo.io/) is a A fast, simple & powerful blog framework, powered by Node.js. 

# Java Development

[Back to the Top](https://github.com/mikeroyal/Raspberry-Pi-Guide/blob/main/README.md#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/93925952-c0b6fd80-fccb-11ea-9f90-21c4148e3c86.png">
  <br />
</p>


## Java Learning Resources

[Java](https://www.oracle.com/java/) is a popular programming language and development platform(JDK). It reduces costs, shortens development timeframes, drives innovation, and improves application services. With millions of developers running more than 51 billion Java Virtual Machines worldwide.

[The Eclipse Foundation](https://www.eclipse.org/downloads/) is home to a worldwide community of developers, the Eclipse IDE, Jakarta EE and over 375 open source projects, including runtimes, tools and frameworks for Java and other languages.

[Getting Started with Java](https://docs.oracle.com/javase/tutorial/)

[Oracle Java certifications from Oracle University](https://education.oracle.com/java-certification-benefits)

[Google Developers Training](https://developers.google.com/training/)

[Google Developers Certification](https://developers.google.com/certification/)

[Java Tutorial by W3Schools](https://www.w3schools.com/java/)

[Building Your First Android App in Java](codelabs.developers.google.com/codelabs/build-your-first-android-app/)

[Getting Started with Java in Visual Studio Code](https://code.visualstudio.com/docs/java/java-tutorial)

[Google Java Style Guide](https://google.github.io/styleguide/javaguide.html)

[AOSP Java Code Style for Contributors](https://source.android.com/setup/contribute/code-style)

[Chromium Java style guide](https://chromium.googlesource.com/chromium/src/+/master/styleguide/java/java.md)

[Get Started with OR-Tools for Java](https://developers.google.com/optimization/introduction/java)

[Getting started with Java Tool Installer task for Azure Pipelines](https://docs.microsoft.com/en-us/azure/devops/pipelines/tasks/tool/java-tool-installer)

[Gradle User Manual](https://docs.gradle.org/current/userguide/userguide.html)

## Tools

[Java SE](https://www.oracle.com/java/technologies/javase/tools-jsp.html) contains several tools to assist in program development and debugging, and in the monitoring and troubleshooting of production applications. 

[JDK Development Tools](https://docs.oracle.com/javase/7/docs/technotes/tools/) includes the Java Web Start Tools (javaws) Java Troubleshooting, Profiling, Monitoring and Management Tools (jcmd, jconsole, jmc, jvisualvm); and Java Web Services Tools (schemagen, wsgen, wsimport, xjc).

[Android Studio](https://developer.android.com/studio/) is the official integrated development environment for Google's Android operating system, built on JetBrains' IntelliJ IDEA software and designed specifically for Android development. Availble on Windows, macOS, Linux, Chrome OS.

[IntelliJ IDEA](https://www.jetbrains.com/idea/) is an IDE for Java, but it also understands and provides intelligent coding assistance for a large variety of other languages such as Kotlin, SQL, JPQL, HTML, JavaScript, etc., even if the language expression is injected into a String literal in your Java code.

[NetBeans](https://netbeans.org/features/java/index.html) is an IDE provides Java developers with all the tools needed to create professional desktop, mobile and enterprise applications. Creating, Editing, and Refactoring. The IDE provides wizards and templates to let you create Java EE, Java SE, and Java ME applications.

[Java Design Patterns ](https://github.com/iluwatar/java-design-patterns) is a collection of the best formalized practices a programmer can use to solve common problems when designing an application or system.

[Elasticsearch](https://www.elastic.co/products/elasticsearch) is a distributed RESTful search engine built for the cloud written in Java.

[RxJava](https://github.com/ReactiveX/RxJava) is a Java VM implementation of [Reactive Extensions](http://reactivex.io/): a library for composing asynchronous and event-based programs by using observable sequences. It extends the [observer pattern](http://en.wikipedia.org/wiki/Observer_pattern) to support sequences of data/events and adds operators that allow you to compose sequences together declaratively while abstracting away concerns about things like low-level threading, synchronization, thread-safety and concurrent data structures.

[Guava](https://github.com/google/guava) is a set of core Java libraries from Google that includes new collection types (such as multimap and multiset), immutable collections, a graph library, and utilities for concurrency, I/O, hashing, caching, primitives, strings, and more! It is widely used on most Java projects within Google, and widely used by many other companies as well.

[okhttp](https://square.github.io/okhttp/) is a HTTP client for Java and Kotlin developed by Square. 

[Retrofit](https://square.github.io/retrofit/) is a type-safe HTTP client for Android and Java develped by Square.

[LeakCanary](https://square.github.io/leakcanary/) is a memory leak detection library for Android develped by Square.

[Apache Spark](https://spark.apache.org/) is a unified analytics engine for large-scale data processing. It provides high-level APIs in Scala, Java, Python, and R, and an optimized engine that supports general computation graphs for data analysis. It also supports a rich set of higher-level tools including Spark SQL for SQL and DataFrames, MLlib for machine learning, GraphX for graph processing, and Structured Streaming for stream processing.

[Apache Flink](https://flink.apache.org/) is an open source stream processing framework with powerful stream- and batch-processing capabilities with elegant and fluent APIs in Java and Scala.

[Fastjson](https://github.com/alibaba/fastjson/wiki) is a Java library that can be used to convert Java Objects into their JSON representation. It can also be used to convert a JSON string to an equivalent Java object.

[libGDX](https://libgdx.com/) is a cross-platform Java game development framework based on OpenGL (ES) that works on Windows, Linux, Mac OS X, Android, your WebGL enabled browser and iOS.

[Jenkins](https://www.jenkins.io/) is the leading open-source automation server. Built with Java, it provides over 1700 [plugins](https://plugins.jenkins.io/) to support automating virtually anything, so that humans can actually spend their time doing things machines cannot.

[DBeaver](https://dbeaver.io/) is a free multi-platform database tool for developers, SQL programmers, database administrators and analysts. Supports any database which has JDBC driver (which basically means - ANY database). EE version also supports non-JDBC datasources (MongoDB, Cassandra, Redis, DynamoDB, etc).

[Redisson](https://redisson.pro/) is a Redis Java client with features of In-Memory Data Grid. Over 50 Redis based Java objects and services: Set, Multimap, SortedSet, Map, List, Queue, Deque, Semaphore, Lock, AtomicLong, Map Reduce, Publish / Subscribe, Bloom filter, Spring Cache, Tomcat, Scheduler, JCache API, Hibernate, MyBatis, RPC, and local cache.

[GraalVM](https://www.graalvm.org/) is a universal virtual machine for running applications written in JavaScript, Python, Ruby, R, JVM-based languages like Java, Scala, Clojure, Kotlin, and LLVM-based languages such as C and C++.

[Gradle](https://gradle.org/) is a build automation tool for multi-language software development. From mobile apps to microservices, from small startups to big enterprises, Gradle helps teams build, automate and deliver better software, faster. Write in Java, C++, Python or your language of choice. 

[Apache Groovy](http://www.groovy-lang.org/) is a powerful, optionally typed and dynamic language, with static-typing and static compilation capabilities, for the Java platform aimed at improving developer productivity thanks to a concise, familiar and easy to learn syntax. It integrates smoothly with any Java program, and immediately delivers to your application powerful features, including scripting capabilities, Domain-Specific Language authoring, runtime and compile-time meta-programming and functional programming. 

[JaCoCo](https://www.jacoco.org/jacoco/) is a free code coverage library for Java, which has been created by the EclEmma team based on the lessons learned from using and integration existing libraries for many years.

[Apache JMeter](http://jmeter.apache.org/) is  used to test performance both on static and dynamic resources, Web dynamic applications. It also used to simulate a heavy load on a server, group of servers, network or object to test its strength or to analyze overall performance under different load types.

[Junit](https://junit.org/) is a simple framework to write repeatable tests. It is an instance of the xUnit architecture for unit testing frameworks.

[Mockito](https://site.mockito.org/) is the most popular Mocking framework for unit tests written in Java.

[SpotBugs](https://spotbugs.github.io/) is a program which uses static analysis to look for bugs in Java code.

[SpringBoot](https://spring.io/projects/spring-boot) is a great tool that helps you to create Spring-powered, production-grade applications and services with absolute minimum fuss. It takes an opinionated view of the Spring platform so that new and existing users can quickly get to the bits they need.

[YourKit](https://www.yourkit.com/) is a technology leader, creator of the most innovative and intelligent tools for profiling Java & .NET applications.


# Python Development

[Back to the Top](https://github.com/mikeroyal/Raspberry-Pi-Guide/blob/main/README.md#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/93133273-ce490380-f68b-11ea-81d0-7f6a3debe6c0.png">
  <br />
  
</p>


## Python Learning Resources

[Python](https://www.python.org) is an interpreted, high-level programming language. Python is used heavily in the fields of Data Science and Machine Learning. 

[Python Developer’s Guide](https://devguide.python.org) is a comprehensive resource for contributing to Python – for both new and experienced contributors. It is maintained by the same community that maintains Python. 

[Azure Functions Python developer guide](https://docs.microsoft.com/en-us/azure/azure-functions/functions-reference-python) is an introduction to developing Azure Functions using Python. The content below assumes that you've already read the [Azure Functions developers guide](https://docs.microsoft.com/en-us/azure/azure-functions/functions-reference).

[CheckiO](https://checkio.org/) is a programming learning platform and a gamified website that teaches Python through solving code challenges and competing for the most elegant and creative solutions.

[Python Institute](https://pythoninstitute.org)

[PCEP – Certified Entry-Level Python Programmer certification](https://pythoninstitute.org/pcep-certification-entry-level/)

[PCAP – Certified Associate in Python Programming certification](https://pythoninstitute.org/pcap-certification-associate/)

[PCPP – Certified Professional in Python Programming 1 certification](https://pythoninstitute.org/pcpp-certification-professional/)

[PCPP – Certified Professional in Python Programming 2](https://pythoninstitute.org/pcpp-certification-professional/)

[MTA: Introduction to Programming Using Python Certification](https://docs.microsoft.com/en-us/learn/certifications/mta-introduction-to-programming-using-python)

[Getting Started with Python in Visual Studio Code](https://code.visualstudio.com/docs/python/python-tutorial)

[Google's Python Style Guide](https://google.github.io/styleguide/pyguide.html)

[Google's Python Education Class](https://developers.google.com/edu/python/)

[Real Python](https://realpython.com)

[The Python Open Source Computer Science Degree by Forrest Knight](https://github.com/ForrestKnight/open-source-cs-python)

[Intro to Python for Data Science](https://www.datacamp.com/courses/intro-to-python-for-data-science)

[Intro to Python by W3schools](https://www.w3schools.com/python/python_intro.asp)

[Codecademy's Python 3 course](https://www.codecademy.com/learn/learn-python-3)

[Learn Python with Online Courses and Classes from edX](https://www.edx.org/learn/python)

[Python Courses Online from Coursera](https://www.coursera.org/courses?query=python)

## Python Frameworks and Tools

[Python Package Index (PyPI)](https://pypi.org/) is a repository of software for the Python programming language. PyPI helps you find and install software developed and shared by the Python community. 

[PyCharm](https://www.jetbrains.com/pycharm/) is the best IDE I've ever used. With PyCharm, you can access the command line, connect to a database, create a virtual environment, and manage your version control system all in one place, saving time by avoiding constantly switching between windows.

[Python Tools for Visual Studio(PTVS)](https://microsoft.github.io/PTVS/) is a free, open source plugin that turns Visual Studio into a Python IDE. It supports editing, browsing, IntelliSense, mixed Python/C++ debugging, remote Linux/MacOS debugging, profiling, IPython, and web development with Django and other frameworks.

[Pylance](https://github.com/microsoft/pylance-release) is an extension that works alongside Python in Visual Studio Code to provide performant language support. Under the hood, Pylance is powered by Pyright, Microsoft's static type checking tool.

[Pyright](https://github.com/Microsoft/pyright) is a fast type checker meant for large Python source bases. It can run in a “watch” mode and performs fast incremental updates when files are modified.

[Django](https://www.djangoproject.com/) is a high-level Python Web framework that encourages rapid development and clean, pragmatic design.

[Flask](https://flask.palletsprojects.com/) is a micro web framework written in Python. It is classified as a microframework because it does not require particular tools or libraries. 
 
[Web2py](http://web2py.com/) is an open-source web application framework written in Python allowing allows web developers to program dynamic web content. One web2py instance can run multiple web sites using different databases.

[AWS Chalice](https://github.com/aws/chalice) is a framework for writing serverless apps in python. It allows you to quickly create and deploy applications that use AWS Lambda. 

[Tornado](https://www.tornadoweb.org/) is a Python web framework and asynchronous networking library. Tornado uses a non-blocking network I/O, which can scale to tens of thousands of open connections.

[HTTPie](https://github.com/httpie/httpie) is a command line HTTP client that makes CLI interaction with web services as easy as possible. HTTPie is designed for testing, debugging, and generally interacting with APIs & HTTP servers. 

[Scrapy](https://scrapy.org/) is a fast high-level web crawling and web scraping framework, used to crawl websites and extract structured data from their pages. It can be used for a wide range of purposes, from data mining to monitoring and automated testing.

[Sentry](https://sentry.io/) is a service that helps you monitor and fix crashes in realtime. The server is in Python, but it contains a full API for sending events from any language, in any application.

[Pipenv](https://github.com/pypa/pipenv) is a tool that aims to bring the best of all packaging worlds (bundler, composer, npm, cargo, yarn, etc.) to the Python world.

[Python Fire](https://github.com/google/python-fire) is a library for automatically generating command line interfaces (CLIs) from absolutely any Python object.

[Bottle](https://github.com/bottlepy/bottle) is a fast, simple and lightweight [WSGI](https://www.wsgi.org/) micro web-framework for Python. It is distributed as a single file module and has no dependencies other than the [Python Standard Library](https://docs.python.org/library/).

[CherryPy](https://cherrypy.org) is a minimalist Python object-oriented HTTP web framework.

[Sanic](https://github.com/huge-success/sanic) is a Python 3.6+ web server and web framework that's written to go fast. 

[Pyramid](https://trypyramid.com) is a small and fast open source Python web framework. It makes real-world web application development and deployment more fun and more productive.

[TurboGears](https://turbogears.org) is a hybrid web framework able to act both as a Full Stack framework or as a Microframework. 

[Falcon](https://falconframework.org/) is a reliable, high-performance Python web framework for building large-scale app backends and microservices with support for MongoDB, Pluggable Applications and autogenerated Admin.

[Neural Network Intelligence(NNI)](https://github.com/microsoft/nni) is an open source AutoML toolkit for automate machine learning lifecycle, including [Feature Engineering](https://github.com/microsoft/nni/blob/master/docs/en_US/FeatureEngineering/Overview.md), [Neural Architecture Search](https://github.com/microsoft/nni/blob/master/docs/en_US/NAS/Overview.md), [Model Compression](https://github.com/microsoft/nni/blob/master/docs/en_US/Compressor/Overview.md) and [Hyperparameter Tuning](https://github.com/microsoft/nni/blob/master/docs/en_US/Tuner/BuiltinTuner.md).

[Dash](https://plotly.com/dash) is a popular Python framework for building ML & data science web apps for Python, R, Julia, and Jupyter.

[Luigi](https://github.com/spotify/luigi) is a Python module that helps you build complex pipelines of batch jobs. It handles dependency resolution, workflow management, visualization etc. It also comes with Hadoop support built-in.

[Locust](https://github.com/locustio/locust) is an easy to use, scriptable and scalable performance testing tool. 

[spaCy](https://github.com/explosion/spaCy) is a library for advanced Natural Language Processing in Python and Cython. 

[NumPy](https://www.numpy.org/) is the fundamental package needed for scientific computing with Python.

[Pillow](https://python-pillow.org/) is a friendly PIL(Python Imaging Library) fork.

[IPython](https://ipython.org/) is a command shell for interactive computing in multiple programming languages, originally developed for the Python programming language, that offers enhanced introspection, rich media, additional shell syntax, tab completion, and rich history.

[GraphLab Create](https://turi.com/) is a Python library, backed by a C++ engine, for quickly building large-scale, high-performance machine learning models.

[Pandas](https://pandas.pydata.org/) is a fast, powerful, and easy to use open source data structrures, data analysis and manipulation tool, built on top of the Python programming language.

[PuLP](https://coin-or.github.io/pulp/) is an Linear Programming modeler written in python. PuLP can generate LP files and call on use highly optimized solvers, GLPK, COIN CLP/CBC, CPLEX, and GUROBI, to solve these linear problems.

[Matplotlib](https://matplotlib.org/) is a 2D plotting library for creating static, animated, and interactive visualizations in Python. Matplotlib produces publication-quality figures in a variety of hardcopy formats and interactive environments across platforms.

[Scikit-Learn](https://scikit-learn.org/stable/index.html) is a simple and efficient tool for data mining and data analysis. It is built on NumPy,SciPy, and mathplotlib.


# Rust Development

[Back to the Top](https://github.com/mikeroyal/Raspberry-Pi-Guide/blob/main/README.md#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/93025405-8dc98700-f5b2-11ea-93f9-12b4a0ef3001.png">
  <br />
</p>


## Rust Learning Resources

[Rust](https://www.rust-lang.org) is a multi-paradigm programming language focused on performance and safety. Rust has a comparable amount of runtime to C and C++, and has set up its standard library to be amenable towards OS development. Specifically, the standard library is split into two parts: core and std. Core is the lowest-level aspects only, and doesn't include things like allocation, threading, and other higher-level features.

[The Rust Language Reference](https://doc.rust-lang.org/nightly/reference/)

[The Rust Programming Language Book](https://doc.rust-lang.org/book/)

[Learning Rust](https://www.rust-lang.org/learn)

[Why AWS loves Rust](https://aws.amazon.com/blogs/opensource/why-aws-loves-rust-and-how-wed-like-to-help/)

[Rust Programming courses on Udemy](https://www.udemy.com/courses/search/?src=ukw&q=Rust)

[Safety in Systems Programming with Rust at Standford by Ryan Eberhardt](https://reberhardt.com/blog/2020/10/05/designing-a-new-class-at-stanford-safety-in-systems-programming.html)

[WebAssembly meets Kubernetes with Krustlet using Rust](https://cloudblogs.microsoft.com/opensource/2020/04/07/announcing-krustlet-kubernetes-rust-kubelet-webassembly-wasm/)

[Microsoft's Project Verona](https://github.com/microsoft/verona/blob/master/docs/explore.md)

## Rust Tools

[Cargo](https://github.com/rust-lang/cargo) is a package manager that downloads your Rust project’s dependencies and compiles your project.

[Crater](https://crater.rust-lang.org/) is a tool to run experiments across parts of the Rust ecosystem. Its primary purpose is to detect regressions in the Rust compiler, and it does this by building a large number of crates, running their test suites and comparing the results between two versions of the Rust compiler. It can operate locally (with Docker as the only dependency) or distributed on the cloud. It can operate locally (with Docker as the only dependency) or distributed on the cloud.

[VSCode-Rust](https://github.com/rust-lang/vscode-rust) is plugin that adds language support for Rust to Visual Studio Code. Rust support is powered by a separate language server - either by the official Rust Language Server (RLS) or rust-analyzer, depending on the user's preference. If you don't have it installed, the extension will install it for you (with permission). This extension is built and maintained by the Rust IDEs and editors team with the focus on providing a stable, high quality extension that makes the best use of the respective language server. 

[Apache Arrow](https://github.com/apache/arrow) is a development platform for in-memory analytics. It contains a set of technologies that enable big data systems to process and move data fast. Arrow's libraries are available for C, C++, C#, Go, Java, JavaScript, MATLAB, Python, R, Ruby, and Rust.

[Wasmer](https://wasmer.io/) enables super lightweight containers based on [WebAssembly](https://webassembly.org/) that can run anywhere such as the Desktop to the Cloud and IoT devices, and also embedded in [any programming language](https://github.com/wasmerio/wasmer#language-integrations).

[Firecracker](https://firecracker-microvm.github.io) is an open source virtualization technology that is purpose-built for creating and managing secure, multi-tenant container and function-based services that provide serverless operational models. Firecracker runs workloads in lightweight virtual machines, called microVMs, which combine the security and isolation properties provided by hardware virtualization technology with the speed and flexibility of containers. Firecracker has also been integrated in container runtimes, for example [Kata Containers](https://github.com/kata-containers/documentation/wiki/Initial-release-of-Kata-Containers-with-Firecracker-support) and [Weaveworks Ignite](https://github.com/weaveworks/ignite).

[Tokio](https://github.com/tokio-rs/tokio) is an event-driven, non-blocking I/O platform for writing asynchronous applications with the Rust programming language.

[TiKV](https://github.com/tikv/tikv) is an open-source distributed transactional key-value database that also provides classical key-vlue APIs, but also transactional APIs with ACID compliance.

[Sonic](https://crates.io/crates/sonic-server) is a fast, lightweight and schema-less search backend similar to Elasticsearch in some use-cases.

[Hyper](https://github.com/hyperium/hyper) is a fast and correct HTTP library for Rust.

[Rocket](https://github.com/SergioBenitez/Rocket) is an async web framework for Rust with a focus on usability, security, extensibility, and speed.

[Clippy](https://rust-lang.github.io/rust-clippy/) is a collection of lints to catch common mistakes and improve your Rust code.

[Servo](https://github.com/servo/servo) is a prototype web browser engine written in the Rust language.

[Vector](https://vector.dev/) is a high-performance, end-to-end (agent & aggregator) observability data platform that puts the user in control of their observability data.

[RustPython](https://github.com/RustPython/RustPython) is a Python Interpreter written in Rust.

[Miri](https://github.com/rust-lang/miri) is an interpreter for Rust's mid-level intermediate representation. It can run binaries and test suites of cargo projects and detect certain classes of undefined behavior. Miri will alsowill also tell you about memory leaks: when there is memory still allocated at the end of the execution, and that memory is not reachable from a global static, Miri will raise an error.

[Chalk](https://rust-lang.github.io/chalk/book/) is an implementation and definition of the Rust trait system using a PROLOG-like logic solver.

[stdarch](https://doc.rust-lang.org/stable/core/arch/) is Rust's standard library vendor-specific APIs and run-time feature detection.

[Simpleinfra](https://github.com/rust-lang/simpleinfra) is rep that contains the tools and automation written by the Rust infrastructure team to manage our services. Using some of the tools in this repo require privileges only infra team members have.

[Rustlings](https://github.com/rust-lang/rustlings) is a small set of exercises to get you used to reading and writing Rust code.

[Krustlet](https://krustlet.dev/) acts as a Kubernetes Kubelet(written in Rust) by listening on the event stream for new pods that the scheduler assigns to it based on specific Kubernetes [tolerations](https://kubernetes.io/docs/concepts/configuration/taint-and-toleration/). The project is currently experimental.

## Operating System

[Redox](https://www.redox-os.org) is a Unix-like Operating System written in Rust, aiming to bring the innovations of Rust to a modern microkernel and full set of applications. Acitvely being developed by [Jeremy Soeller](https://gitlab.redox-os.org/jackpot51).

[Bottlerocket OS](https://github.com/bottlerocket-os/bottlerocket) is an open-source Linux-based operating system meant for hosting containers. Bottlerocket focuses on security and maintainability, providing a reliable, consistent, and safe platform for container-based workloads.

[Tock](https://www.tockos.org) is an embedded operating system designed for running multiple concurrent, mutually distrustful applications on Cortex-M and RISC-V based embedded platforms. Tock's design centers around protection, both from potentially malicious applications and from device drivers. Tock uses two mechanisms to protect different components of the operating system. First, the kernel and device drivers are written in Rust, a systems programming language that provides compile-time memory safety, type safety and strict aliasing. Tock uses Rust to protect the kernel (the scheduler and hardware abstraction layer) from platform specific device drivers as well as isolate device drivers from each other. Second, Tock uses memory protection units to isolate applications from each other and the kernel.

[Rust on Chrome OS](https://chromium.googlesource.com/chromiumos/docs/+/master/rust_on_cros.md) is a document that provides information on creating Rust projects for installation within Chrome OS and Chrome OS SDK. 

[Writing an OS in Rust ](https://os.phil-opp.com) is a blog series creates a small operating system in the Rust programming language by [Philipp Oppermann](https://github.com/phil-opp). 


# TypeScript Development

[Back to the Top](https://github.com/mikeroyal/Raspberry-Pi-Guide/blob/main/README.md#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/93133287-d1dc8a80-f68b-11ea-94d3-bba83dd5b0bb.png">
  <br />

</p>

## TypeScript Learning Resources

[TypeScript](https://www.typescriptlang.org) is a language for application-scale JavaScript. TypeScript adds optional types to JavaScript that support tools for large-scale JavaScript applications for any browser, for any host, on any OS. TypeScript compiles to readable, standards-based JavaScript.

[TypeScript support for Webpack](https://webpack.js.org/guides/typescript/)

[TypeScript Support for Nuxt.js](https://typescript.nuxtjs.org)

[TypeScript Support for Vue.js](https://vuejs.org/v2/guide/typescript.html)

[TypeScript Support for React Native](https://reactnative.dev/docs/typescript)

[TypeScript Support for Angular](https://angular.io/guide/typescript-configuration)

[Ionic/TypeScript Starter Project](http://justin-credible.github.io/Ionic-TypeScript-Starter/)

[GitHub Actions for JavaScript and TypeScript](https://docs.github.com/en/actions/language-and-framework-guides/github-actions-for-javascript-and-typescript)

## Tools

[WebStorm](https://www.jetbrains.com/webstorm/) is a professional IDE for JavaScript(including support for both HTML and CSS) developed by JetBrains. WebStorm comes with intelligent code completion, on-the-fly error detection, powerful navigation and refactoring for JavaScript, TypeScript, stylesheet languages, and all the most popular frameworks([Angular](https://angular.io/), [React](https://reactjs.org/), [Vue.js](https://vuejs.org/), [Ionic](https://ionicframework.com/), [Apache Cordova](https://cordova.apache.org/), [React Native](https://reactnative.dev/), [Node.js](https://nodejs.org/), [Meteor](https://www.meteor.com/#!), and [Electron](https://www.electronjs.org/)).

[ReSharper](https://www.jetbrains.com/resharper/) is a Visual Studio Extension for .NET Developers. It comes with code quality analysis, which is available in C#, VB.NET, XAML, ASP.NET, ASP.NET MVC, JavaScript, TypeScript, CSS, HTML, and XML. You'll know right away if your code needs to be improved. ReSharper is one of many powerful tools developed by [JetBrains](https://www.jetbrains.com).

[ts-migrate](https://github.com/airbnb/ts-migrate) is a tool for helping migrate code to TypeScript. It takes a JavaScript, or a partial TypeScript, project in and gives a compiling TypeScript project out. ts-migrate is intended to accelerate the TypeScript migration process. The resulting code will pass the build, but a followup is required to improve type safety.

[Deno](https://deno.land) is a simple, modern and secure runtime for JavaScript and TypeScript that uses V8 and is built in Rust.

[gulp-typescript](https://github.com/ivogabe/gulp-typescript) is an TypeScript compiler for gulp with incremental compilation support.

[React](https://reactjs.org/) is a declarative, efficient, and flexible JavaScript library for building user interfaces.

[React Native](https://reactnative.dev) is a framework for building native apps for iOS and Android with React.

[Vue.js](http://vuejs.org/) is a progressive, incrementally-adoptable JavaScript framework for building UI on the web.

[Angular](https://www.angular.io/) is a development platform for building mobile and desktop web applications using Typescript/JavaScript and other languages.

[Ionic Framework](https://ionicframework.com/) is a powerful cross-platform UI toolkit for building native-quality iOS, Android, and Progressive Web Apps with HTML, CSS, and JavaScript.

[Stencil](https://stenciljs.com/) is a simple compiler for generating Web Components and static site generated progressive web apps (PWA). Stencil was built by the Ionic team for its next generation of performant mobile and desktop Web Components.

[Storybook](https://storybook.js.org/) is a development environment for UI components. It allows you to browse a component library, view the different states of each component, and interactively develop and test components.It works with React, Vue, Angular, Ember, and other web frameworks.

[Prettier](https://prettier.io/) is an opinionated code formatter. It enforces a consistent style by parsing your code and re-printing it with its own rules that take the maximum line length into account, wrapping code when necessary.

[Nest](https://nestjs.com/) is a framework for building efficient, scalable [Node.js](http://nodejs.org/) server-side applications. It is built with TypeScript and combines elements of Object Oriented Programming(OOP), Functional Programming, and Functional Reactive Programming(FRP).

[Definitely Typed](https://github.com/DefinitelyTyped/DefinitelyTyped) is a repository for high quality TypeScript type definitions.

[TypeORM](https://github.com/typeorm/typeorm) is an ORM that can run in NodeJS, Browser, Cordova, PhoneGap, Ionic, React Native, NativeScript, Expo, and Electron platforms and can be used with TypeScript and JavaScript (ES5, ES6, ES7, ES8).

[NativeScript](https://www.nativescript.org/) empowers you to access native APIs from JavaScript directly. The framework currently provides iOS and Android runtimes for rich mobile development and can be utilized in a number of diverse use cases.

[AssemblyScript](https://assemblyscript.org/) compiles a strict variant of TypeScript to [WebAssembly](http://webassembly.org/) using [Binaryen](https://github.com/WebAssembly/binaryen).

[React Hook Form](https://react-hook-form.com/) is a performant, flexible and extensible forms with easy to use validation(Web + React Native).

[Apollo Client](https://apollographql.com/client) is a fully-featured caching GraphQL client with integrations for React, Angular, and more. It allows you to easily build UI components that fetch data via GraphQL.

[TensorFlow.js](https://js.tensorflow.org/) is an open-source WebGL hardware-accelerated JavaScript library for training and deploying machine learning models.

[Rome](https://romefrontend.dev/) is a linter, compiler, bundler, and [more](https://romefrontend.dev/#development-status) for JavaScript, TypeScript, JSON, HTML, Markdown, and CSS.

[Eclipse Theia](https://github.com/eclipse-theia/theia) is an extensible platform to develop full-fledged multi-language Cloud & Desktop IDE-like products with state-of-the-art web technologies.

[InversifyJS](https://github.com/inversify/InversifyJS) is a powerful and lightweight inversion of control(IoC) container for JavaScript & Node.js apps powered by TypeScript. An IoC container uses a class constructor to identify and inject its dependencies.

[Gatsby](https://www.gatsbyjs.com/) is a free and open source framework based on React that helps developers build blazing fast websites and apps.

[Meteor](https://www.meteor.com/) is an ultra-simple environment for building modern web applications with JavavScript. 

[TypeScript ESLint](https://typescript-eslint.io/) is a monorepo for all the tooling which enables ESLint to support TypeScript.

[TS node](https://github.com/TypeStrong/ts-node) is a TypeScript execution and REPL for node.js.


#  HMTL/CSS Development

[Back to the Top](https://github.com/mikeroyal/Raspberry-Pi-Guide/blob/main/README.md#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/95024326-33fb3080-0637-11eb-9ecc-156776139eb4.png">
  <br />
</p>

## HMTL/CSS Learning Resources

[HTML (HyperText Markup Language)](https://developer.mozilla.org/en-US/docs/Web/HTML) is the basic building blocks of the Web. It defines the meaning and structure of web content along with other technologies used to describe a web page's appearance/presentation using CSS or functionality/behavior using JavaScript.

[Cascading Style Sheets (CSS)](https://developer.mozilla.org/en-US/docs/Web/CSS) is a stylesheet language used to describe the presentation of a document written in HTML or XML (including XML dialects such as SVG, MathML or XHTML). CSS also describes how elements should be rendered on screen, on paper, in speech, or on other media.

[Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html)

[Airbnb CSS / Sass Style Guide](https://github.com/airbnb/css)

[HTML Styles CSS](https://www.w3schools.com/html/html_css.asp)

[CSS Tutorial](https://www.w3schools.com/Css/)

[Microsoft Certified Solutions Associate (MCSA): Web Applications](https://docs.microsoft.com/en-us/learn/certifications/mcsa-web-applications-certification)

[Intro to HTML/CSS: Making webpages by Khanacademy](https://www.khanacademy.org/computing/computer-programming/html-css)

[Intro to HTML and CSS by Udacity](https://www.udacity.com/course/intro-to-html-and-css--ud001)

[Learn to style HTML using CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS)

[The HTML and CSS Workshop](https://www.packtpub.com/product/the-html-and-css-workshop/9781838824532)

[Modern HTML & CSS From The Beginning (Including Sass) by Udemy](https://www.udemy.com/course/modern-html-css-from-the-beginning/)

[Using Glitch for Developer Relations](https://glitch.dev)

## HMTL/CSS Tools

[WebStorm](https://www.jetbrains.com/webstorm/) is a professional IDE for JavaScript(including support for both HTML and CSS) developed by JetBrains. WebStorm comes with intelligent code completion, on-the-fly error detection, powerful navigation and refactoring for JavaScript, TypeScript, stylesheet languages, and all the most popular frameworks([Angular](https://angular.io/), [React](https://reactjs.org/), [Vue.js](https://vuejs.org/), [Ionic](https://ionicframework.com/), [Apache Cordova](https://cordova.apache.org/), [React Native](https://reactnative.dev/), [Node.js](https://nodejs.org/), [Meteor](https://www.meteor.com/#!), and [Electron](https://www.electronjs.org/)).

[Codeanywhere](https://codeanywhere.com/) is a Cloud Integrated Development Environment. Our Cloud IDE saves you time by deploying a development environment in seconds, enabling you to code, learn, build, and collaborate on your projects.

[Adobe Brackets](https://github.com/adobe/brackets) is a modern open-source code editor for HTML, CSS and JavaScript that's built in HTML, CSS and JavaScript.

[Ultimate CSS Gradient Generator](https://www.colorzilla.com/gradient-editor/) is a powerful Photoshop-like CSS gradient editor from [ColorZilla](https://www.colorzilla.com).

[CSS Gradient](https://cssgradient.io/) is a happy little website and free tool that lets you create a gradient background for websites.

[Glitch](https://glitch.com) makes easier to build fast, full-stack web apps in your browser for free.

[CSS Optimizer](https://www.csstidyonline.com) is an online tool to clean, compress, and optimize your CSS code.

[Sciter](https://github.com/c-smile/sciter-sdk) is an embeddable HTML/CSS/scripting engine, Windows, MacOS and Linux.

[Flexy](https://vladocar.github.io/flexy/) is minimal CSS framework made with Flex.

[Simple CSS](https://www.hostm.com/css) is a tool that allows you to easily create Cascading Style Sheets from scratch, and modify existing ones, using a familiar point-and-click interface. With Simple CSS, you can manage multiple CSS projects, import existing .css files as desired, and export projects to .css files.

[Conditional-CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Conditional_Rules) is a CSS module that allows to define a set of rules that will only apply based on the capabilities of the processor or the document the style sheet is being applied to.

[Kotatsu](https://github.com/Yomguithereal/kotatsu) is a straightforward CLI tool aiming either at running node.js scripts or serving JavaScript/TypeScript web applications in a modern environment.

[AWK](https://awk.js.org/) is a scripting language used for manipulating data and generating reports.


# Ruby Development

[Back to the Top](https://github.com/mikeroyal/Raspberry-Pi-Guide/blob/main/README.md#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/93719684-07282300-fb39-11ea-98fd-90394a2df6f2.png">
  <br />
</p>


## Ruby Learning Resources

[Ruby](https://www.ruby-lang.org/en/) is a dynamic, open source programming language with a focus on simplicity and productivity. It has an elegant syntax that is natural to read and easy to write.

[Ruby Documentation](https://www.ruby-lang.org/en/documentation/)

[Ruby Community](https://www.ruby-lang.org/en/community/)

[Ruby Gems](https://guides.rubygems.org/rubygems-basics/)

[Ruby courses by Coursera](https://www.coursera.org/courses?query=ruby)

[Learn Ruby course by Codecademy](https://www.codecademy.com/learn/learn-ruby)

[Ruby Glossary](https://www.codecademy.com/articles/glossary-ruby)

[Ruby in Twenty Minutes Quickstart](https://www.ruby-lang.org/en/documentation/quickstart/)

[Getting started with a Ruby on Rails application on CircleCI.](https://circleci.com/docs/2.0/language-ruby/)

[The Ruby Style Guide](https://rubystyle.guide)

[Airbnb's Ruby Style Guide](https://github.com/airbnb/ruby)

## Tools

[RubyMine](https://www.jetbrains.com/ruby/) is a professional IDE developed by Jet Brains that provides support for Ruby, Ruby on Rails and web development.

[Rails](https://rubyonrails.org/) is a web-application framework that includes everything needed to create database-backed web applications according to the [Model-View-Controller (MVC)](https://en.wikipedia.org/wiki/Model-view-controller) pattern. Understanding the MVC pattern is key to understanding Rails. MVC divides your application into three layers: Model, View, and Controller, each with a specific responsibility.

[rbenv](https://github.com/rbenv/rbenv) allows to pick a Ruby version for your application and guarantee that your development environment matches production. Put rbenv to work with Bundler for painless Ruby upgrades and bulletproof deployments.

[Prettier for Ruby](https://prettier.io/) is a plugin for the Ruby programming language and its ecosystem. prettier is an opinionated code formatter that supports multiple languages and integrates with most editors. The idea is to eliminate discussions of style in code review and allow developers to get back to thinking about code design instead.

[Active Admin](https://activeadmin.info/) is a Ruby on Rails framework for creating elegant backends for website administration.

[Capistrano](https://github.com/capistrano/capistrano) is a framework for building automated deployment scripts. Although Capistrano itself is written in Ruby, it can easily be used to deploy projects of any language or framework, be it Rails, Java, or PHP.

[Spree](https://spreecommerce.org/) is an open source E-commerce platform for Rails 6 with a modern UX, optional PWA frontend, REST API, GraphQL, several official extensions and 3rd party integrations.

[Sidekiq](https://sidekiq.org/) is a simple, efficient background processing for Ruby. It uses hreads to handle many jobs at the same time in the same process. It does not require Rails but will integrate tightly with Rails to make background processing dead simple.

[Kaminari](https://github.com/amatsuda/kaminari/wiki) is a  Scope and Engine based, clean, powerful, and customizable  paginator for modern web app frameworks and ORMs.

[React-Rails](https://github.com/reactjs/react-rails) is a flexible tool to use [React](http://facebook.github.io/react/) with Rails. By integrating React.js with Rails views and controllers, the asset pipeline, or webpacker.

[Pry](https://github.com/pry/pry) is a runtime developer console and IRB alternative with powerful introspection capabilities.

[Brakeman](https://brakemanscanner.org/) is a static analysis tool which checks Ruby on Rails applications for security vulnerabilities.

[dotenv](https://github.com/bkeepers/dotenv) is a Ruby gem to load environment variables from `.env`.

[Scientist](https://github.com/github/scientist) is a Ruby library for carefully refactoring critical paths.

[fastlane](https://fastlane.tools/) is a tool written in Ruby for iOS and Android developers to automate tedious tasks like generating screenshots, dealing with provisioning profiles, and releasing your application.

[Fluentd](https://www.fluentd.org/) collects events from various data sources and writes them to files, RDBMS, NoSQL, IaaS, SaaS, Hadoop and so on all written in Ruby.


# PHP Development

[Back to the Top](https://github.com/mikeroyal/Raspberry-Pi-Guide/blob/main/README.md#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/93925949-bf85d080-fccb-11ea-9158-d8d967a03e60.png">
  <br />
 
</p>


## PHP Learning Resources

[PHP](https://www.php.net/) is a popular general-purpose scripting language that is especially suited to web development. Fast, flexible and pragmatic, PHP powers everything from your blog to the most popular websites in the world.

[PHP 8](https://www.php.net/releases/8.0/en.php)

[What's New in PHP 8 - Auth0](https://auth0.com/blog/whats-new-php-8/)

[PHP Manual](https://www.php.net/manual/en/index.php)

[MIT's PHP Code Style Guide](https://mitsloan.mit.edu/shared/content/PHP_Code_Style_Guide.php)

[PHP Style Guide](https://gist.github.com/ryansechrest/8138375)

[PHP tutorial by W3Schools](https://www.w3schools.com/php/)

[PHP MySQL & CodeIgniter Course on Udemy](https://www.udemy.com/course/php-mysql-codeigniter-complete-guide/)

## Tools

[PhpStorm](https://www.jetbrains.com/phpstorm/) is a professional PHP IDE developed by Jet Brains for working with Symfony, Laravel, Drupal, WordPress, Laminas, Magento, Joomla!, CakePHP, Yii, and other frameworks.

[Laravel](https://laravel.com/) is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling.

[PHP Tools for Visual Studio/VS Code](https://www.devsense.com/en) is a an extension that turn Visual Studio into a powerful PHP development environment.

[Symfony](https://symfony.com/) is a PHP framework for web and console applications and a set of reusable PHP components. Symfony is used by thousands of web applications (including BlaBlaCar.com and Spotify.com) and most of the [popular PHP projects](https://symfony.com/projects) (including Drupal and Magento).

[CakePHP](https://cakephp.org) is a rapid development framework for PHP which uses commonly known design patterns like Associative Data Mapping, Front Controller, and MVC. CakePHP's main goal is to provide a structured framework that enables PHP users at all levels to rapidly develop robust web applications, without any loss to flexibility.

[Composer](https://getcomposer.org/) is a tools helps you declare, manage, and install dependencies of PHP projects.

[Guzzle](https://github.com/guzzle/guzzle) is a PHP HTTP client that makes it easy to send HTTP requests and trivial to integrate with web services.

[DesignPatternsPHP](https://designpatternsphp.readthedocs.io/) is a collection of known design patterns and some sample code how to implement them in PHP 7.4. Every pattern has a small list of examples.

[CodeIgniter](https://codeigniter.com/) is an Application Development Framework for people who build web sites using PHP. Its goal is to enable you to develop projects much faster than you could if you were writing code from scratch, by providing a rich set of libraries for commonly needed tasks, as well as a simple interface and logical structure to access these libraries. CodeIgniter lets you creatively focus on your project by minimizing the amount of code needed for a given task.

[HHVM](https://hhvm.com/) is an open-source virtual machine designed for executing programs written in [Hack](https://hacklang.org/). HHVM uses a just-in-time (JIT) compilation approach to achieve superior performance while maintaining amazing development flexibility. HHVM should be used together with a webserver like the built in, easy to deploy [Proxygen](https://docs.hhvm.com/hhvm/basic-usage/proxygen), or a [FastCGI-based](https://docs.hhvm.com/hhvm/advanced-usage/fastCGI) webserver on top of nginx or Apache.

[PHPUnit](https://phpunit.de/) is a programmer-oriented testing framework for PHP. It is an instance of the xUnit architecture for unit testing frameworks.

[Phalcon](https://phalcon.io/) is an open source web framework delivered as a C extension for the PHP language providing high performance and lower resource consumption.

[Swoole](https://www.swoole.co.uk/) is an event-driven asynchronous & coroutine-based concurrency networking communication engine with high performance written in C and C++ for PHP.

[Matomo](https://matomo.org/) is a full-featured PHP MySQL software program that you download and install on your own webserver. At the end of the five-minute installation process, you will be given a JavaScript code. Simply copy and paste this tag on websites you wish to track and access your analytics reports in real-time.

[Grav](https://getgrav.org/) is a Fast, Simple, and Flexible, file-based Web-platform. There is Zero installation required. Just extract the ZIP archive, and you are already up and running. It follows similar principles to other flat-file CMS platforms, but has a different design philosophy than most. Grav comes with a powerful Package Management System to allow for simple installation and upgrading of plugins and themes, as well as simple updating of Grav itself.

[Whoops](https://filp.github.io/whoops/) is an error handler framework for PHP. Out-of-the-box, it provides a pretty error interface that helps you debug your web projects, but at heart it's a simple yet powerful stacked error handling system.

[Slim](https://www.slimframework.com/) is a PHP micro framework that helps you quickly write simple yet powerful web applications and APIs. 


## Contribute

- [x] If would you like to contribute to this guide simply make a [Pull Request](https://github.com/mikeroyal/Raspberry-Pi-Guide/pulls).


## License
[Back to the Top](https://github.com/mikeroyal/Raspberry-Pi-Guide/blob/master/README.md#table-of-contents)

Distributed under the [Creative Commons Attribution 4.0 International (CC BY 4.0) Public License](https://creativecommons.org/licenses/by/4.0/).
