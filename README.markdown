Flip Clock Screen Saver
=======================

I love minimal screen savers and was impressed by [Fliqlo][1], a screen saver
that mimics a simple flip clock. It runs on Mac and Windows by using Adobe
Flash.

Unfortunately, it has a bug on some Macs where when the machine comes out of
the screen saver state, your mouse cursor could be missing until you click in a
text field. Also, in my case, I uninstalled Flash on my machine so the screen
saver doesn't work.

I decided to try and duplicate the functionality entirely in [Quartz
Composer][2], a nifty tool for wiring up all kinds of graphics processing
visually. Any Quartz Composer document can be used as a screen saver on a Mac
without any extra kind of processing. Just plop the file in `~/Library/Screen
Savers` and then you can choose it.

All the graphics are generated on the fly by Quartz. It's functional, but it
doesn't do any actual flipping animation at this point. I'd love for some
suggestions on how to do that. Or, just fork the project and try for yourself!


## To Install

Copy the flipclock.qtz file to `~/Library/Screen Savers` and then open the
"Desktop and Screen Savers" preference pane in "System Preferences". Choose
`flipclock` from the list of screen savers, and enjoy!


## I need HELP!

Alas, this is my first experiment with Quartz Composer. Feel free to shoot me a
message through Github, but don't expect any expert reply. You can open up the
`qtz` file yourself in Quartz Composer and see how it works.



  [1]: http://www.9031.com/downloads/screensavers.html
  [2]: http://developer.apple.com/graphicsimaging/quartz/quartzcomposer.html
