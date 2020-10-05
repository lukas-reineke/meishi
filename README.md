
# Meishi


This is my business card, as well as a QMK powered macro keyboard.

<img src="https://i.imgur.com/c9RAzk4.jpg" width="900">
<img src="https://i.imgur.com/A8b0177.jpg" width="900">

## Parts Needed

- 1 PCB
- 1 Pro Micro (or compatible controller)
- 2 Pro Micro standoffs (usually included when buying a Pro Micro)
- 4 MX switches
- 4 MX keycaps
- 4 rubber feet (optional)

## Build

Solder the Pro Micro _face down_ onto the PCB with standoffs.

Solder the MX switches.

## Firmware

The card uses QMK as the firmware. To setup QMK, please referee to the [QMK Docs](https://docs.qmk.fm/#/)

The pinout is the same as [Biacco42/meishi](https://github.com/Biacco42/meishi).
It can be flashed with the same configuration.

```bash
make meishi:default:avrdude
```

To reset the Pro Micro, short the RESET pin to ground.

