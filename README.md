# Urchin w/ Dongle Firmware

Firmware designed to be used with the Urchin keyboard and a Seeed XIAO BLE wireless dongle.

## Overview

This firmware enables wireless connectivity for the Urchin keyboard using a Seeed XIAO BLE dongle. It provides seamless multi-device wireless communication with full ZMK Studio compatibility for configuration and monitoring.

## Features

- USB dongle form factor (Seeed XIAO BLE)
- ZMK Studio support for real-time monitoring and configuration

## Hardware Requirements

- **Dongle**: Prospector - Seeed XIAO BLE (nRF52840)
- **Keyboard Halves**: Nice!Nano (nRF52840) microcontrollers
- **USB Connection**: USB-C adapter/cable

## Getting Started

### Prerequisites

- [ZMK Firmware](https://zmk.dev) knowledge
- Git
- Two keyboard halves with Nice!Nano controllers

### Building

Firmware is automatically built and released via GitHub Actions.

1. Clone this repository
2. Configure your ZMK settings in `config/`
3. Build the dongle firmware via Github Actions
4. Flash the dongle and keyboard halves with their respective firmware

## Configuration

Configuration files are located in the `config/` directory. Refer to [ZMK Documentation](https://zmk.dev/docs) for detailed configuration options.

## Resources

- [ZMK Documentation](https://zmk.dev)
- [ZMK Studio](https://studio.zmk.dev)
- [Seeed XIAO BLE](https://wiki.seeedstudio.com/XIAO_BLE)

## Credits

- [duckyb](https://github.com/duckyb)
- [carrefinho](https://github.com/carrefinho)
- [M165437](https://github.com/M165437)

## License

See LICENSE file for details.
