# Elecrow-LCD35

Unofficial Driver (but working) and User manual for 3.5 inch LCD Touchscreen for Raspberry Pi 2 and 3.

## How to Install

Download or clone this repo on your Raspberry Pi:

```
git clone https://github.com/panahbiru/Elecrow-LCD35.git
```

Install xserver evdev packages:

```
cd Elecrow-LCD35
sudo dpkg -i xserver-xorg-input-evdev_2.10.5-1_armhf.deb
```

Install Elecrow Driver with this command:
```
sudo chmod +x Elecrow-LCD35
sudo ./Elecrow-LCD35
```

### How to Calibrate Touchscreen

Install the touchscreen calibration package 
```
cd Elecrow-LCD35
sudo dpkg -i xinput-calibrator_0.7.5-1_armhf.deb
```

then click Raspbian Start Menu -> Preference -> Calibration Touchscreen. Follow the instruction.
