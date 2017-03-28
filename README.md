# temp-monitor
A simple temperature monitor for Linux based systems. The code is set to loop a 100 times with 1 second gaps inbetween. You can change the number of loops and the gap time to fit your needs.

The only thing that is needed for this script to work is a package called "sensors". You can easily install it with the command:
<code>sudo apt install sensors</code>

Be sure to place the file in the root directory. Then just type <code>./temp</code> to run it. 

To stop the script, use <code>Ctrl + C</code>.

Example:

<code>
You need to install lm-sensors sudo apt install lm-sensors
</code>
<br>
<code>
acpitz-virtual-0
</code>
<br>
<code>
Adapter: Virtual device
</code>
<br>
<code>
temp1:        +60.8°C  (crit = +104.8°C)
</code>

Enjoy :)
