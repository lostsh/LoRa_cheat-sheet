# Getting Started
Petite aide mémoire, allègrement basé sur la super doc de [meshtastic](https://meshtastic.org/docs/introduction/).

[<img src="https://flasher.meshtastic.org/img/devices/seeed-xiao-s3.svg" alt="esp32-s3 board" style="width:200px;"/>](https://meshtastic.org/docs/introduction/)

## Setup

Packages: python3, python3-pip, python3-venv

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade esptool
```

Check on serial com : esptool chip_id

## Download firmware

[Github firwmare release](https://github.com/meshtastic/firmware/releases/tag/v2.5.20.4c97351)

[firmware-esp32s3-2.5](https://github.com/meshtastic/firmware/releases/download/v2.5.20.4c97351/firmware-esp32s3-2.5.20.4c97351.zip)


## Install

Install
```bash
tall.sh -f firmware-BOARD-VERSION.bin
```
Update
```bash
./device-update.sh -f firmware-BOARD-VERSION-update.bin
```
