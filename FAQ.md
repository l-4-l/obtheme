1. Are you going to add an image preview like the one in ObConf?
Ideally, yes. I just don't know how to (yet). I'll try to figure out how ObConf does it and see if there's a way to do it in pygtk. If that doesn't work, maybe I'll just ask the ObConf devs to create a stand-alone previewer that I could embed. I promise nothing though.

2. What's up with the code? Why isn't it more pythonic?
I was almost completely new to Python when I wrote it. I also hacked most of it together over 3 days and never went back to clean it up. I'll get to it eventually.

3. I'm not using Arch Linux... how do I install it?
Just download the source tarball, unpack it and run obtheme. Make sure that you have python-fuse and pygtk (the latest version). If you really want to install it, package it for your distro's package manager so that obtheme is placed in your path. I'll get around to adding an install script eventually but it's not a priority right now as I don't even know if anyone is using this on something other than Arch Linux.
