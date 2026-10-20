# README

This project is a modified version of Starbie, the week 1 project for the Half-Life competition. This project includes
all the default features of Starbie, except this time with a rechargable battery and a joystick for additional interactivity.

It also bears the shape of a floppy disk, instead of a star, and has a different pet than the default "Sparkle".

I made this for week 1 on the Half-Life Hack Club competition, using KiCad.

Assembly:
Firstly, get the ESP32 in place, on the bottom-right of the board, there are pads and traces just fit for it! use those exact pads and traces, and orient the ESP32 in a way so that it's facing to the outside of the board, not inside. on J4, solder the JST connector to the board, so that positive is on the right, next, on R1, solder the resistor so that the positive input goes to 3.3v. Next to it is where the DHT 11 sensor will go, the square hole is where positive 3.3V will go. Just above is J2, where the MPU6050 will go, once again, the square hole is where 3.3 is on the sensor. Above that, towards the top is the 2 switches, solder those 2 as well, it's impossible to mess this up unless you're soldering to the backside, which you shouldn't be anyway. Finally is the joystick, where once again the square pin is used for alignment, but instead that's where ground goes. Smack dab in the middle is the OLED, where once again you have to just not be an idiot.

Before you can turn it on, you must flash the ESP-32, download the .ino file and plug the ESP32 in, then just flash it with the Arduino software like any other board, make sure the settings are correct though.

doomguy-starbie render:
<img width="765" height="488" alt="image" src="https://github.com/user-attachments/assets/a8772a8c-b4b0-48da-b237-ee9f1f627c99" />

schematic:
<img width="627" height="537" alt="image" src="https://github.com/user-attachments/assets/4a8a9487-c964-4d1c-b842-5bed381acd29" />

pcb:
<img width="379" height="353" alt="image" src="https://github.com/user-attachments/assets/4b5e9941-f059-4e07-947a-62db5b33ae14" />
