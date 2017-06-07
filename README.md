![Elite logo](elitelogo.png?raw=true)
# CMDJamski-T16000M-FCS-HOTAS v1.0
An ever expanding Elite Dangerous control scheme for the Thrustmaster T16000M FCS HOTAS system

This is a WIP control scheme for the Thrustmaster T.16000M FCS HOTAS system.  I really didn't like the layout of the default scheme provided by Elite Dangerous so I set about modifying it to my liking.

# Ship Controls

A fair number of the controls haven't changed but there were too many key functions for things like combat that were mapped to the buttons on the base of the stick, which in combat made them next to useless.

What was the ships boost button has been turned into an ALT button for accessing multiple functions on the same buttons.  Having a dedicated boost button was too dangerous - it nearly cost me an Anaconda!

# SRV Controls

The SRV controls are almost identical to the ship controls. 

# Camera Controls

There is a pretty full compliment of camera controls included in the mapping, including control for the free camera.

# Unmapped Controllers

So far nothing has been mapped to the castle hat on the throttle but in a future version this could be used for the wingman controls.

# TARGET Software Issues

This supplied control scheme does not require TARGET to be installed.  If you want to use this mapping you can safely uninstall the TARGET programming suite.

When I first attempted to use the TARGET software the stick was rendered completely inoperable.  The TARGET software installs and manages a virtual device and then controls the game through a profile.  On many systems it seems that this virtual device is problematic and conflicts with Windows power management.

If I find the need in the future to go deeper into the programming of this HOTAS I will investigate the power management issues some more and offer up some kind of batch file for configuring this but so far I have been happy with just plain mapping the physical controls of the HOTAS.

# Installation Instructions

To install the mapping you need to find your local Bindings directory.  You'll probably find it here:

C:\Users\<your user name>\AppData\Local\Frontier Developments\Elite Dangerous\Options\Bindings

Copy these two files into that location:

CMDJamski-T16000M-FCS-HOTAS-V1.0.2.0.binds
StartPreset.start

Then startup your game.  By including this StartPreset.start file you are simply configuring this mapping as the default one to use.

# Cheat Sheet

I've created a cheat sheet that details all the included mappings which you can see below.  Download and keep it for reference.

![Cheat Sheet](CMDRJamski-TM-FCS-CheatSheet.png?raw=true "Cheat Sheet")

# Reporting Issues

If you find any problems or what you consider to be a better idea for the mapping open a GitHub issue for discussion and/or fix.

HAPPY FLIGHTS AHOY!!

O7

CMDRJamski over and out!