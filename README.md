# Nemo-K temperature sensor for DS18B20

## Overview

This is Nemo-K board for ESP-01 and well-known [DS18B20](https://www.analog.com/en/products/ds18b20.html) gauge.

Because of its measuring range (-55°C to +125°C, -67°F to +257°F) DS18B20 is ideal for all marine temperature
measurements e.g. salons, engine coolant, engine room. However, using this gauge for measuring except exhaust
pipe temperatures is out of its range.

The board is designed to be used with ESP-01 microcontroller running Nemo-K firmware.

## Content

The repository contains schematics and PCB in KiCad 8.0 format. The footprint properties contains LCSC part numbers
used by [JLCPBC.com](https://jlcpcb.com). If present, the `sensor-temp-ds18b20/production/` contains all necessary
files to order boards from JLCPCB. The production files can be easily re-created using
[KiCad Fabrication Toolkit](https://github.com/bennymeg/Fabrication-Toolkit).

The Nemo-K project is not affiliated or sponsored by JLCPCB. The project does not endorse JLCPCB.

## Changelog

* *v2* First working version. The labels "Sens Data" and "Sens 3.3V" of the temperature sensor screw terminal
  are the wrong way around. A reverse polarity protection diode should be added.

## Copyright and License

The license and copyright can be found in the file `LICENSE`.

The license and copyright cover only the schematic diagram and the PCB design. It does not cover footprints and other
embedded elements or technical documentation which may or may not be covered by their own licenses.
