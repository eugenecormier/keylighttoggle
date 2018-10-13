This script toggles the keyboard backlights on and off like a mute on volume. After it's been turned off, running the script again returns the keyboard backlights to their previous brightness. I wrote this to make my keyboard backlights behave like my screen backlight when my laptop goes into powersave/dimmed mode. It can be started by calling it with xautolock before your screensaver/locker, but I never did figure out a wakeup hook to call it again to reset the lights.

Invocation
---------------
Run the script, run it again. Then run it... maybe one more time?


Variables
---------------
'filename' where you want to store your previous value
'currentname' the /sys/class location of your keyboard leds brightness file


Dependancies
---------------
None
