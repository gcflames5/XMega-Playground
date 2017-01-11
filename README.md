XMega Playground
====

Overview
----
This board serves as a place where users can practice various aspects of embedded programming using an XMega(128/64/32)A4U. The first version of this board is focused heavily on testing various types of communication protocols, featuring USB, Serial, CAN, SPI, and I2C. Additionally, the board includes a pair of 7 segment displays, and 10 LEDs (4 are digital RGB LEDs) to allow a degree of output to the user. For use with these various communication protocols, this board includes an separate ADC (with pressure and temperature sensors), flash memory IC, TTL to RS-232 level shifter, CAN transciever, and two IMUs.

<img src="http://i.imgur.com/2d5tRro.png" width="600" height="600">

List of Features (version 1.0)
----
 - 2 7-segment displays (driven by shift registers)
 - 4 WS2812B digital RHB leds
 - 6 0805 LEDs
 - CAN Transciever
 - RS-232 to TTL level shifter
 - 2 IMUs: Acceleration, Magetometer
 - ADC (w/ 2.5V reference chip)
   - Temperature sensor
   - Ambient pressure sensor
 - Flash Memory
 - Current Sense Op Amp
   - Configurable load for testing

Considerations for Future Versions
----
 - Add a character LCD display for more useful output to the user
 - Break out more GPIO pins into headers
 - Expand number of 7 segment displays
 - Utilize DAC and waveform generation, include H-bridge, microphone, speaker, etc.