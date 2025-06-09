# Simple-2040-knob
 PCB Design for a single rotary encoder HID, based on a RP2040 microcontroller.

## About
The goal of this project was to get more practice designing PCBs by implementing a microcontroller directly on a PCB. The current iteration successfully works except for USB programming and communication. USB power works, and programming over the SWD pins also works demonstrating that the RP2040 and flash were correctly configured including the crystal oscillator (at least for the simple led blink code tested on the device).

## Future Changes
*	Shorten the USB traces, use a surface mount usb port and double check impedance so USB communication will work.
*	Replace the crystal circuit with an external crystal oscillator IC which would hopefully be simpler to implement and more robust.
*	Add hardware debouncing to the encoder implementation.
