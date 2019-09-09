---
title: Real-Time Object Tracking system
subtitle: My B.Sc. Thesis "Design and Implementation of a Real-Time Object Tracking system"
summary: My B.Sc. Thesis "Design and Implementation of a Real-Time Object Tracking system"
#date: 2019-07-12
math: true
diagram: true
markup: mmark
#image:
#placement: 3
#caption: 'Image credit: [**John Moeses Bauan**](https://unsplash.com/photos/OGZtQF8iC0g)'
---
**Implementation of a GPS-GSM Tracking System, Monitored in a Mobile App based on Google Map.** <br>
Available in: [GitHub](https://github.com/sarehsoltani/RealTimeTrackerSystem.git).
<p align="center">
  <img width="700" height="400" src="https://user-images.githubusercontent.com/23232055/59965808-357b1500-9528-11e9-9e5c-2229ae5d681d.jpg">
</p>

In this project, we intend to implement a system that can accurately determine the location, direction of movement, and locations of moving objects at any given time with using SIM808 Module. In this system, each object is equipped with a GPS module that receives its location every two minutes from the satellite and sends it to the software servers via the GSM modem. Software servers analyze the information after receiving it. In this part of the project, a web application will be developed to process the transmitted data and then store it in a database and finally convert the stored information to visible to users. This allows you to see the speed, direction of movement, and locations of the object on the map.
<br>
<br>
This project is a simple tracking system that uses the same GSM and GPS module that is built 
into the SIM808 module. whenever you send the “Hi” or “Hello” string to the number of that SIM
 that is already inserted in the GSM Module, you will be able to get a response with the GPS location of the module depending on where it is. <br>
<br>
Hardware and Software Requirements: <br>
**Hardware**
- SIM 808 Module 
- Arduino UNO OR Arduino MEGA 
- Arduino cable
- 9V supply
- GPS antenna and GSM antenna 

**Software**
- Arduino IDE
- SIM808 library

Connections for the Arduino UNO:
<p align="center">
  <img width="500" align="center" height="300" src="https://user-images.githubusercontent.com/23232055/64549661-6bb97b00-d346-11e9-90bb-5afb3129d616.jpeg">
</p>

The designed Tracker System:

<p align="center">
  <img width="500" align="center" height="300" src="https://user-images.githubusercontent.com/23232055/64449151-8f858280-d0f4-11e9-9bcc-d22a6d768da8.PNG">
</p>