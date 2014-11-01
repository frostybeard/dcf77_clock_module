# Arduino libraries for the DCF77

## DCF77

Libraries for Arduino to connect to the DCF77 clock receiver module from Conrad Electronic

Original DCF77 library version is from:
https://github.com/thijse/Arduino-Libraries/tree/master/DCF77


The DCF77 library adds the ability to read and decode the atomic time broadcasted by the 
DCF77 radiostation. It has been designed to work in conjunction with the Arduino Time 
library and allows a sketch to get the precise CET time and date as a standard C time_t.
The DCF77 Library download. Example sketches have been added to 
1) illustrate and debug the incoming signal 
2) use the library, using the setSyncProvider callback and converting to different 
   time zones. In order to exploit all features in the library, Both the Time and 
   TimeZone library are included.


## Time

This library is from:
http://playground.arduino.cc/Code/Time

It differs as of 1 Nov. 2014 from that version that is available for download there.
Some files have been patched for the "const" compiler errors seen in later Arduino
IDE versions. (See the git version history)


