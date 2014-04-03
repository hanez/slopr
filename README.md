slopr - screen lock on phone remove
=====

A small daemon for locking the screen when removing a phone from an inductive 
USB phone charger on Linux

Description
-----------

slopr is using libusb for getting information about the current power 
consumption of a USB device. slopr will be configured by the following 
parameters at start time.

	--command	/the/command/to/execute/on/event
	--device	/proc/path/to/device
	--threshold	300

If the current power consumption of the "device" falls below the "threshold"
the "command" will be executed.

More to come... ;)
