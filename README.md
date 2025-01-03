# Multi-USB-camera-app
Camera app for driving multiple USB based cameras using the UVC protocol. With the objective to create a 3D camera app with real cameras.
The idea is to have an app on a smartphone able to control 2 or more external USB connected cameras. These USB cameras are connected through a USB hub. 
The user of this application has its focus on photography, the quality of the image is important as well as video.
There are other possibilities for shooting 3D content, I am very aware of that, but this app allows a lot of freedom in setting up your camera configuration which no other 3D camera solution has, meaning the hardwardware. It can be very small or big, portable or in a fixed configuration.
The app should allow users to set the cameras to the appropiate equal settings, depending on the camera's specific capabilities. This can be limited to exposure only but could be extended to control apperture, shutter time and many other settings.
For 3D the chalange is to be able to synchronize all the triggered cameras in one time. Simple cameras do not have the facility to control this. However there are cameras using external trigger pins or timecode options. The app should do its work with or without these options.
the app could be written using Open Camera or Camera2 Api for example. 
The chalange could be the interface with the cameras, powering them, controlling them. 
There is no idea about the User interface.
Post processing of the 3D content would be a nice to have feature. Or could be integrated from other software.
I did some tests with small USB modules and cameras and it seems to work on a very simple way using the USB Dual Camera app. But this app is very limited in features.

This first initial post is to call for open source developpers to help and build this application. I do not have enough experience to write code for android or IOS. 
