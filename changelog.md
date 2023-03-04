Changelog:

Sadek Baroudi: 2022-12-15
-------------------------------
removed leftover decoupling capactiors, no longer needed
removed one of the shift registers
added two thumbs in the center
changed 2U to 1U and shifted keys inwards
redid routing so that front side is vertical, and backside is horizontal
fixed schematic
	* elite-c / nice nano
	* shift register
	* removed all the extra stuff that's no longer on the pcb
redid the switch matrix to use less cols to support the single shift register, and maximized gpio
added jlcpcb pcba support
other general cleanup...


Dasky: 2022-12-22
-------------------------------
add led power selection jumper raw/vcc
add led power switch circuit
added per key rgb
replaced ws2812b underglow with sk6803 mini-e
rotated all switches
rerouted pcb
add .gitignore
clean up backup files


Mabroum: 2022-12-23
-------------------------------
Add Splay
Moved thumb tucky
Add auto render bot

Bomtarnes: 2023-03-04
-------------------------------
Add solenoid circuitry and forehead to place it
Rounded corners on edgecuts in fusion360

bom's bom
https://www.digikey.com/en/products/detail/w%C3%BCrth-elektronik/694106301002/5047522 - barrel jack x1
https://www.digikey.com/en/products/detail/onsemi/1N4001/976982 - flyback diodes x2
https://www.digikey.com/en/products/detail/DIP05-1A72-11L/374-1051-ND/2171028 - reed relay x1
https://www.digikey.com/en/products/detail/adafruit-industries-llc/412/5819056 - solenoid x1
https://www.digikey.com/en/products/detail/stmicroelectronics/TIP120/603564 - npn darlington transistor x1
