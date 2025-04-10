# GlitchPixel404
A small and portable WLED driver board designed for powering digital addressable LED strips in art installations at Camp 404 during AfrikaBurn.

## Features

* Compact PCB design
* ESP32-PICO-MINI module
* 3 buffered output channels with compact screw terminals
* 5A PTC fuse protection (Global)
* Supports 5V, 12V, and 24V digital addressable LED strips
* USB-C and 2.1mm DC jack power inputs
* USB PD support for selectable 5V, 12V, or 20V output(Works with most 24V LED strips)
* MOSFET/Relay for power control of LED strips
* Single onboard Neopixel for status indication
* Onboard I2S microphone for audio-reactive effects
* Designed for a 3D printed case

## Hardware

* Based on the ESP32-PICO-MINI module.
* Insipired by the [Adafruit Sparkle Motion](https://www.adafruit.com/product/6100) controller and other OSHW WLED projects.

## Software

* Intended for use with the [WLED firmware](https://kno.wled.ge/).
* Advanced audio and group control by [LedFx](https://github.com/LedFx/LedFx) 

## License

This project is open-source under the [CC BY-SA 4.0](license.txt).

## Intended Use

Designed for powering creative LED lighting installations.

## Status

Currently in the PCB design phase.

## Contributing

Contributions are welcome!

## Acknowledgements

* This project utilises the fantastic [WLED](https://kno.wled.ge/) firmware.
* Inspired by the vibrant creativity of [Camp 404](https://github.com/404camp/) and [AfrikaBurn](https://www.afrikaburn.com/).