# Rc-planes-live-map
Android application for viewing rc planes in real map

# Description

With this project the pilot has the ability to monitor the flight path of his rc plane on a map via a mobile phone in real time !
The pilot connects through a small ESP32 board linked to their transmitter (TX16 and others).

Using the Android application, the pilot can view the planes’s route as well as the positions of real airplanes flying in the area, helping to avoid potential hazards. No adsb required !
Additionally, the system can connect with other transmitters located nearby to enable live flight relaying.

Anyone who has the application installed, and logged in as a registrated user, will be able to view the flight of all binded rc planes in real time !
An additional feature is that, as mentioned, multiple pilots can connect with each other to fly in formation or engage in chasing, allowing them to “locate each other.” 
The screen includes a dashboard that displays the distance and altitude of the two aircraft, while an audio proximity alert is also provided so pilots don’t have to constantly look at their phone.
The mobile application is still under development, and more features will be added later.

# Target Frames  
Fpv planes, drones, cars  etc. 

# Connections
A connection with radio transmitter required (has been tested with radiomaster TX16s).
Connect a small esp32 board with the uart port of the TX16s. (telemetry mirror).
https://www.waveshare.com/wiki/ESP32-S3-Zero



# How to install
Download all files and extract them to your pc into a single directory. For example C:\\live_map.

1.Copy the android aplication file (APK) "TX16S_Live_Map.apk" to your phone and install it.

2.Double Click the esp32_File_1.bat for plane 1.This will flash the esp32 board for 1st plane.

3.Double Click the esp32_File_2.bat for plane 2.This will flash the esp32 board for 2nd plane.
  Only two planes permited at the moment.

# Photos





![Screenshot_2025-10-02-12-11-25-458_com example tx16map](https://github.com/user-attachments/assets/a2c94be7-645e-4272-b4dd-a893a10ff6c3)




