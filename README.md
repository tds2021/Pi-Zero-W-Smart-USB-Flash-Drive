# Pi Zero W Smart USB Flash Drive
SMB enabled network share that appears as a USB drive to connected device

## Acknowledgements

This project is not an original idea.  It is based on the work documented in the MagPi magazine [article](https://magpi.raspberrypi.org/articles/pi-zero-w-smart-usb-flash-drive) by the same name.  It was written by [Russell Barnes](https://magpi.raspberrypi.org/articles/author/77pb3df8MQLs3i8qTd0C8Q). It also barrows some ideas from this [project](https://github.com/gilesdavison/RadaDASH) by [Giles Davison](https://github.com/gilesdavison).

## Features
* Remotly accessabel USB device (uploading, deleting)
* 2GB shared storage pre configured (default)
* Create AnyCubic WIFI.txt file based on the Raspberry PI's configuration

## Printer Support
This project should work for most (if not all) 3D printers.  However, it was created with the [ANYCUBIC Photon Mono X](https://www.anycubic.com/products/photon-mono-x-resin-printer) in mind. There is an optional service that can be enabled to dynamically create a WIFI.txt file in the ANYCUBIC format to help configure the printer to match the netowrk configured on the Raspberry Pi W.

## Prerequisites

* MicroSD Card >= 8GB
* MicroSD Card Adapter/Reader
* USB to Micro USB Cable
* [Raspberry Pi Zero W](https://www.raspberrypi.org/products/raspberry-pi-zero-w/)*

*Note, will not work on other Raspberry Pi's since they do not support USB OTG.

## Setup Instructions
