# Eli's weatherClock #

An digital analog clock but instead of showing the hours, the clock shows the weather at that hour of the day. So instead of showing 1, it will show the weather forecast for 1AM/PM. Click on the hour for more detailed information such as wind, precipitation and more. Once in the detailed view, simply click the center again to return to the analog clock face.

You will need to:
- Install a full Raspbian distribution (not lite)
- Install python ```pynput``` module. Pynput needs X11 which is on full Raspbian distributions.
- Obtain your own OpenWeatherMap API key from https://openweathermap.org/ and change your location
- Setup the Pi to push display to the Pimoroni screen: https://learn.pimoroni.com/tutorial/sandyj/getting-started-with-hyperpixel-4

---

In my testing setup I use a Pi Zero W with a Pimoroni 4" touchscreen.

I have experienced an issue with running this on the Pi Zero W - after a few days, the program starts to get super slow and at some point the program closes itself.

For any questions/comments - you can open an issue or contact me directly at k3vinwu25@gmail.com 

Youtube video showing the clock: https://youtu.be/qGV7r33nt4c

CAD files for enclosure located here: https://cad.onshape.com/documents/a04351220114f9397820b114/w/0854a09a8bd19b8df2167e54/e/af44268ed043f94be60c93c6
Instructions for setting up the display (go to the "Setting up your Raspberry Pi" section): https://learn.pimoroni.com/tutorial/sandyj/getting-started-with-hyperpixel-4

