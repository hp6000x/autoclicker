# What is it?

It's a few sample BASH scripts showing you how to use xdotool to create an autoclicker for modded Minecraft or whatever other game or app might make use of one.

# What do I need?

Only a handful of things:

	1: A Computer running some variation of Linux
	2: BASH (Most distros have BASH pre-installed. If you're running a distro that doesn't use BASH as it's defult shell, you probably know how to change it.)
	3: xdotool (Get it from the repository. If you don't know how to install apps on your distro, just google "how do I install xdotool on {my distro}?" there's plenty of guides out there)
	4: These scripts. Put them in $HOME/bin or wherever you like, just don't forget where you put them.
	5: The program or game you want to autoclick on.

# How do I use these scripts?

Here's an example of how to use them with a Minecraft Gardens of Glass modpack that has Tree Growing Simulator, all on Xubuntu:

	1: Open the settings app and go to keyboard settings
	2: Go to the keyboard shortcuts tab and click on the button labelled "New"
	3: For the command, enter:
		/path/to/xdotool rightclick 500
	4: Press the keys you want to trigger the clicker. For the key combination, use something like Shift-Super-J or whatever super-key combinations aren't used. Remember what you picked. "Super" is the windows logo key, btw
	5: Create another shortcut with the "New" button
	6: For the command, enter:
		/path/to/xdotool shifter 500
	7: Pick another key combination
	8: Launch Minecraft
	9: Go to your Gardens of Glass world, look at the ground, hit your key combination, hold shift and BOOM! Pebbles galore!
	10: Then when you have some saplings, plant them and hit the second key combination for rapid growth.

For other distros, look up how to create keyboard shortcuts and mimic the process above. For other games and other things than just shift, and left- and right-clicks, have a look at the code, xdotool --help and man xdotool. It's a very versatile tool that can automate a variety of tasks!
