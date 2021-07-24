# HomeWavePush
Vera / OpenLuup plugin for the HomeWave app

Installing:
Use the Alternative App Store, or manually upload the files.  Then create a device 

Configuration:
Create a new device, and specify D_HWPush1.xml amd I_HWPush1.xml as the device and implementation files respectively
Open the device, and set your HomeWave Push ID (20 characters minimum), and enter the same ID that you configured in the HomeWave app
Hit the Test button to send a test message to your phone.

Use:
You can send messages from scenes by using the SendMessage action, specifying the message and optionally the name of the sound to play.  (See https://homewave.intvelt.com for a list of these sounds)
