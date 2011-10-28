You can program the Trackuino board using a standard ICSP programmer, such
as AVR-ISP, however you can use a regular Arduino as an external programmer,
this schematic shows how to do it.

You need to:

1. Remove the Atmega328p chip from the Arduino board.

2. Wire the Arduino and the Trackuino according to the schematic (just
take a look at the PDF file, you don't really need the Eagle files)

3. Use the Bitbang method described here to burn the trackuino .hex:
http://www.geocities.co.jp/arduino_diecimila/bootloader/index_en.html

(look for the instructions specific to the 328p chip. Instead of the
Arduino bootloader, you will be burning the trackuino .hex file)

