# pyparrot

Python interface for Parrot Drones

pyparrot is designed to program Parrot Mambo and Parrot Bebop 2 drones using python.  This interface was developed to teach kids (K-12) STEM concepts (programming, math, and more) by having them program a drone to fly autonomously.  Anyone can use it who is interested in autonomous drone programming!   

# Installation, Quick-start, Documenation, FAQs
The GitHub [wiki page for pyparrot](https://github.com/amymcgovern/pyparrot/wiki) has extensive documentation on installing and using pyparrot.  

This brench is focusing on the beacon integration and vision based object avoidence approach
# Planned updates/extensions

This is a work in progress.  Planned extensions include:

* **Mambo**
I do not have any Mambo drone so if you are interesed in ask original contributor.
   
* **Bebop**
   * Navigation: I am currently try to integrate the collosion probablity network to preven the accident.
   *Beacon: Marvelmind beacon can give the x,y,z coordinate. Also there is IMU version which can compensate the error of internal autopilot work. I will upload the beacon sdk and how to use it example code. I hope someone suggest or upload the better code for it. I am just student.
   

# Major updates and releases:

* 2/22/2018: Version 1.3.2.  Updated DroneVision to make the vision processing faster.  Interface changed to only have the user call open_vision and close_vision (and not start_video_buffering)
* 2/10/2018: Version 1.3.1. Updated DroneVision to work on Windows.
* 2/8/2018: Version 1.3. Vision is working for both the Mambo and Bebop in a general interface called DroneVision.  Major documenation updates as well.
* 2/6/2018: Updated Mambo to add speed settings for tilt & vertical.  Needed for class.
* 2/4/2018: Unofficial updates to add ffmpeg support to the vision (will make an official release with examples soon)
* 12/09/2017: Version 1.2.  Mambo now gives estimated orientation using quaternions.  Bebop now streams vision, which is accessible via VLC or other video clients.  Coming soon: opencv hooks into the vision.  
* 12/02/2017: Version 1.1.  Fixed sensors with multiple values for Mambo and Bebop.
* 11/26/2017: Initial release, version 1.0.  Working wifi and BLE for Mambo, initial flight for Bebop.

# Programming and using your drones responsibly

It is your job to program and use your drones responsibly!  We are not responsible for any losses or damages of your drones or injuries.  Please fly safely and obey all laws.

