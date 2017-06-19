Basic ESP8266 WeMos Shield
==========================

This shield is used to quickly do some tests/boards with WeMos ESP8266 boards it has just few minimal features.
- I2C Pullups placement
- Classic I2C 128x64 OLED connector (with PAD to reverse 3V3 and GND if needed)
- pad to solder components if needed to
- N-FET placement for 1 signal adapter such as 5V to 3V3

New in Version 1.1
- I2C connector has PAD to reverse 3V3 and GND if needed
- Ground Plane has isolate of 8mil to avoid in some case shorts when soldering

You can find more information on WeMos on their [site][1], it's really well documented.
I now use WeMos boards instead of NodeMCU's one because they're just smaller, features remains the same, but I also suspect WeMos regulator far better quality than the one used on NodeMCU that are just fake of originals AMS117 3V3.

*Boards are ordered as testing from OSHPark, I did not fully tested them yet, I will update as soon has I got them in my hands. Use at your own risks*

Detailed Description
====================

Look at the schematics for more informations.

### Schematic  
![schematic](https://raw.githubusercontent.com/hallard/WeMos-shield/master/WeMos-shield-sch.png)  

### Boards  
<img src="https://raw.githubusercontent.com/hallard/WeMos-shield/master/WeMos-shield-top.png" alt="Top" width="40%" height="40%">&nbsp;
<img src="https://raw.githubusercontent.com/hallard/WeMos-shield/master/WeMos-shield-bot.png" alt="Bottom" width="40%" height="40%">&nbsp; 

You can order the PCB of this board v1.0 at [OSHPARK][3] or V1.1 at [PCBs.io][4]. 
PCBs.io give me some reward when you order my designed boards from their site. This is pretty good, because I can use these rewards to create and design new boards and order boards for a discounted price, so if you don't care about PCB manufacturer please use PCBs.io.


### Assembled boards

I'm currently waiting for boards from OSHPARK

##License

<img alt="Creative Commons Attribution-NonCommercial 4.0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png">   

This work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](http://creativecommons.org/licenses/by-nc/4.0/)    

##Misc
See news and other projects on my [blog][2] 
 
[1]: http://www.wemos.cc/wiki/doku.php?id=en:d1_mini
[2]: https://hallard.me
[3]: https://oshpark.com/shared_projects/rnk2lmmh
[4]: https://PCBs.io/share/zZAJY

