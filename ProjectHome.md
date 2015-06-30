the goal is to create awesome led poi
current dev board spec
6 A6280 LedDrivers
Atmega328p-pu(yays arduino)
sparkfun's 9dof board
6 LRTB\_C9TP(RBG LED's)
Possible Final version spec
9v battery
Atmega328p-mu(VT-200-F XTAL, XC6201 vreg)
LSM330DLC (Accelerometer/gyro)
Not yet found the magnetic compass i want
12 LRTB\_C9TP(RBG LED's)
Still looking for my eeprom
!!!!!This project is open to anyone who wishes to contribute,build or other wise enjoy!!!!!
**Going Thru Some Redesign(got my caps in :-) code = "crap :(") oh well tis the process. hmmm... may be awhile before next status update**
Some Quick Words before any bashing THIS IS JUST FOR FUN :-D
Update:I have removed the shift registers and opted out for softpwm for the betas as im only using 6 leds i have enough i/o pins though im trying to keep the idea of using the shift registers alive and will keep writing code as to make adding leds as simple as possible. Also i have added a foundation for simple text support. Be aware that the text system needs alot of work right now as i want to use the internal eeprom tho store the font. I am also working on some basic wave forms now.