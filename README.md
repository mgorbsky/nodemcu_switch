# nodemcu_switch

This is an attempt to use a NodeMCU board to set a lamp to one of three modes: On, Off, 
and Dim via my existing SmartThings setup in my home.

I'm expecting to use IFTTT to handle the http requests from the NodeMCU board. 

I will likely need to create a new virtual device within my smarttthings account to support 
dimming the lamp to a specified value (IFTTT can only toggle lamps on/off at this time, so I'd
need to toggle on a virtual device, use an event handler to set the lamp to a predefined value
and then reset the virtual device to an off state again.

The goal for this project is to allow my 4 yr old daughter to control the lamp in her room that's
not connected a light switch. I'd like her to be able to turn the ligh on, off, and activate 
a "night light" mode.