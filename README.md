# Awesome ASUS Tinker Board
A curated list of ASUS Tinker Board resources

![Tinker Board Logo](https://github.com/thyrlian/awesome-asus-tinker-board/blob/master/resources/images/tinker_board_logo.png)

## Hardware

### Specifications

**ASUS Tinker Board**

| Component | Details |
| --- | --- |
| CPU | Rockchip Quad-Core RK3288 processor |
| Memory | 2GB Dual Channel DDR3 |
| Graphic | Integrated Graphics Processor<br/>ARM® Mali™-T764 GPU |
| Storage | Micro SD(TF) card slot |
| LAN | RTL GB LAN |
| Wireless Data Network | 802.11 b/g/n, Bluetooth V4.0 + EDR |
| Audio | RTL ALC4040 CODEC |
| USB Ports | 4 x USB 2.0 |
| Internal I/O Ports | **1 x 40-pin header :**<br/><ul><li>up to 28 x GPIO pins</li><li>up to 2 x SPI bus</li><li>up to 2 x I2C bus</li><li>up to 4 x UART</li><li>up to 2 x PWM</li><li>up to 1 x PCM/I2S</li><li>2 x 5V power pins</li><li>2 x 3.3V power pins</li><li>8 x ground pins</li></ul>**1 x 2-pin contact pin :**<br/><ul><li>1 x PWM</li><li>1 x S/PDIF</li></ul>**1 x 15-pin MIPI DSI**<br/>**1 x 15-pin MIPI CSI** |
| Accessories | Passive heatsink<br />User manual |
| Weight | 55g |
| Dimensions | 85.60mm x 56mm x 21mm |

### Power Supply

According to the quick start guide (first edition):
> 1 x Micro USB cable and a **5V/2A** USB power adapter with **LPS** marking

According to the ASUS Tinker Board official page's FAQ:
> Tinker Board supports **5V/1~2.5A** power input, but since the SoC’s performance is high, if the connected
peripheral required huge power demand from the board, it might cause the power supply issue.
Thus we strongly recommended to use the AC adaptor with **5V/2~2.5A** power rating, plus **LPS** marking.

**Battery** supply is also possible, as long as the power output is no less than **5V/1A**.

### Tested Compatible Components

| Category | Model Name |
| --- | --- |
| SD Card | Lexar® Professional 1000x microSDXC™ UHS-II (150MB/s) 64GB |
| Power Adapter | Samsung Travel Adaptor EP-TA10EWE 5.3V/2.0A |

## TinkerOS

A Debian-based distribution ensures a smooth and functional experience.

### Flash OS Image

1. Download [**Etcher**](https://etcher.io/) - a powerful cross-platform open source OS image flasher.
2. Download **TinkerOS**.
3. Uncompress the TinkerOS file, select the **.img** file in Etcher and flash it to the SD card.  (Don't worry about the FS format, Etcher will make it **FAT32** eventually.)

### Authentication

username: `linaro`

password: `linaro`

### Download

**Debian**

| Version | Release Date |
| --- | --- |
| [V1.8 Beta](http://dlcdnet.asus.com/pub/ASUS/mb/Linux/Tinker_Board_2GB/20170417-tinker-board-linaro-stretch-alip-v1.8.zip) | 2017/04/18 |
| [V1.6 Beta](http://dlcdnet.asus.com/pub/ASUS/mb/Linux/Tinker_Board_2GB/20170330-tinker-board-linaro-jessie-alip-v16.zip) | 2017/04/01 |
| [V1.4](http://dlcdnet.asus.com/pub/ASUS/mb/Linux/Tinker_Board_2GB/20170223-tinker-board-linaro-jessie-alip-v14.zip) | 2017/03/10 |
| [V1.3](http://dlcdnet.asus.com/pub/ASUS/mb/Linux/Tinker_Board_2GB/TinkerOS_Debian.zip) | 2017/02/07 |

**Android**

| Version | Release Date |
| --- | --- |
| [V13.11.0.2 Beta](http://dlcdnet.asus.com/pub/ASUS/mb/Linux/Tinker_Board_2GB/20170419-tinkerboard-android-marshmallow-userdebug131102.zip) | 2017/04/20 |

## Links

* [Official Page from ASUS](https://www.asus.com/Single-Board-Computer/Tinker-Board/)
* [Driver & Tools download page](https://www.asus.com/Single-Board-Computer/Tinker-Board/HelpDesk_Download/)
