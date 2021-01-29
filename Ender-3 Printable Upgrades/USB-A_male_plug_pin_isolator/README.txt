                   .:                     :,                                          
,:::::::: ::`      :::                   :::                                          
,:::::::: ::`      :::                   :::                                          
.,,:::,,, ::`.:,   ... .. .:,     .:. ..`... ..`   ..   .:,    .. ::  .::,     .:,`   
   ,::    :::::::  ::, :::::::  `:::::::.,:: :::  ::: .::::::  ::::: ::::::  .::::::  
   ,::    :::::::: ::, :::::::: ::::::::.,:: :::  ::: :::,:::, ::::: ::::::, :::::::: 
   ,::    :::  ::: ::, :::  :::`::.  :::.,::  ::,`::`:::   ::: :::  `::,`   :::   ::: 
   ,::    ::.  ::: ::, ::`  :::.::    ::.,::  :::::: ::::::::: ::`   :::::: ::::::::: 
   ,::    ::.  ::: ::, ::`  :::.::    ::.,::  .::::: ::::::::: ::`    ::::::::::::::: 
   ,::    ::.  ::: ::, ::`  ::: ::: `:::.,::   ::::  :::`  ,,, ::`  .::  :::.::.  ,,, 
   ,::    ::.  ::: ::, ::`  ::: ::::::::.,::   ::::   :::::::` ::`   ::::::: :::::::. 
   ,::    ::.  ::: ::, ::`  :::  :::::::`,::    ::.    :::::`  ::`   ::::::   :::::.  
                                ::,  ,::                               ``             
                                ::::::::                                              
                                 ::::::                                               
                                  `,,`


http://www.thingiverse.com/thing:3044586
USB-A male plug pin isolator by magnurz is licensed under the Creative Commons - Attribution license.
http://creativecommons.org/licenses/by/3.0/

# Summary

This is an odd way to get data-only or power-only USB connections. It's a small "mat" that goes between the pins of the USB plug and the USB socket and disconnects some pins.

For data only the VCC pin is isolated.

For power only the D+ and D- pins are isolated.

I made this because I noticed that when my Ender 3 is powered off but connected to the Raspberry PI / OctoPi it's partially powered through USB backpower. Also a high frequency noise can be heard in this state. It's probably not good for the electronics. Anyway I thought maybe I could make something instead of butchering a USB cable...

The SCAD can be used with customizer to isolate any PINs you want or if you need a different tolerance (higher tolerance makes the mat more narrow and more likely to fit inside the USB plug).

**Note: _Use at your own risk!_** The thing can probably get stuck in the plug. It can probably cause pins to get bent. It can probably fall into your device. You may have to turn your device upside down for this concept to work - be careful! :)

**Note:** Take note that the USB pins push down in the back of the plug, so the part of the mat that is whole goes *in the front*. The photo was a prototype and isn't the final model, but it shows the idea of how to insert this. 

**Note:** Google "USB pinout" to make sure you put the mat into the plug the correct way. The VCC pin is to the right in my photo.

**Note:** MrFoxi has mentioned that USB power may be used while flashing the Ender3/printer firmware, so if you want to do that and you have installed this thing, remove it first.

**Update 12/08/18:** Added GCODEs from Simplify3D. 210 degree Celsius nozzle. 60 degree Celsius bed. Layer height 0.1mm. Extrusion width 0.2mm. 40% outline overlap. Slow speed. Only 1 layer. This worked alright with Creality Ender 3.

**Update 25/05/19:** Stripped prime strip from GCODE files, a couple of people crashed their clips because of it. Sorry about that, Simplify3d has always added that strip for me and I have gotten used to it.


# Print Settings

Printer Brand: Creality
Printer: Ender 3
Rafts: No
Supports: No
Resolution: Layers 0.1mm, extrusion witdth 0.2mm
Infill: NA

Notes: 
You'll want this as thin as possible in the Z direction so it can fit in-between the USB plug and socket pins. You'll probably have to experiment with your printer to get it right.