## Realtek Bluetooth Dongle Driver for Linux

The Orico BT dongle (Model: BTA-508) does not work out of the box on Ubuntu 20.04 (kernel 5.4.0-42).

## Solution

Download the firmware and read the read me inside it.

## Installation

Open your terminal and type this code below:

``` shell
sudo apt install --install-recommends linux-generic-hwe-20.04
```

Clone this repo to your computer:

``` shell
git clone https://github.com/pftmclub/Realtek_Linux_Driver
```

Go to this folder "20201202_LINUX_BT_DRIVER/" and install this using make:

``` shell
sudo make install INTERFACE=all
```

Replug your dongle and start the Bluetooth adapter. 

## Known Issue

Only Ubuntu is supported.
