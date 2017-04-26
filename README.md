# iot-greenhouse-ctrl
IOT greenhouse controller on Raspberry Pi with Python

## What does it do

* Gather relative and soil humidity, greenhouse temperature and outdoor temperature [dev]
* Fan control with linear actuator window opener [dev]
* Irrigation control [dev]

## Wiring

* Brown - BCM27 -> Relay 12VDC open (K1)
* Red - BCM17 -> Relay neutral open (K2)
* Orange - BCM24 -> Relay 12VDC close (K3)
* Yellow - BCM22 -> Relay neutral close (K4)
