# TODO

* ~~Perform some final cleanup and release version 1.5~~
* Attempt to remove reliance on the main thread when disconnecting a device.
Currently used to delay hotplug routine
* Look into distributing profile properties around various objects
rather than using a lot of getters to obtain properties each poll.
It will complicate the architecture a little bit but hopefully
any speed difference will make up for it.
* Remove old welcome dialog and make new driver installer executable.
Use newer standards (WPF) and bundle app with DS4Windows
