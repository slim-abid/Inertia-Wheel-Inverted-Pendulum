# Inertia Wheel Inverted Pendulum Project 

The Inertia Wheel Pendulum is a benchmark for nonlinear control of under actuated mechanical systems consisting of a physical pendulum with a symmetric disk attached to the tip, which is free to spin about an axis parallel to the axis of rotation of the pendulum.   


This project is based on Arduino Mega 2560 R3 microcontroller. And the repo contains 
- LabView project 


 
The full gallery of the project
![173442306_3835249403207891_3843970440395399707_n](https://user-images.githubusercontent.com/52780461/115481307-3ffdb700-a244-11eb-95f7-f7211520bf91.png){ width="350px"}
![172280093_373108927178272_7261096589997962787_n](https://user-images.githubusercontent.com/52780461/115481331-4db33c80-a244-11eb-9815-3a55bfd486aa.jpg) { width="350px"}
![image_2021-04-10_030404](https://user-images.githubusercontent.com/52780461/115481369-61f73980-a244-11eb-92d6-1b1fe1f87d21.png){ width="350px"}


# Electronics hardware
- Arduino Mega 2560 R3 
- customized L293D is a dual-channel H-Bridge motor driver 
- 12V Motor DC 
- Gyroscope
- switch button
- Lipo Battery

# 3D printed parts
-  Inetria wheel - (0.1mm  50+%)
   - Motor shaft mount has to be adapted
   - The two provided wheel STLs are for 14tooth and 12tooth version of motors
   - Feel free to make your own version of the inertia wheel with the solidworks file
-  Motor mount - (0.2mm  30%)
-  Pole shaft connector - (0.1mm  30%)
-  Shaft adapter - (0.1mm  30%)


# Control algorithm
 - PID (Simple)
 - LQR algorithm (Intermediate) - bIncluded in the software
 

# Connecting the hardware
 - Monster motor shield is mounted on Arduino Mega 2560 R3 very simply, as on any Arduino
    - It provides the hardware connections needed and no need for additional jumpers
    - 12V - 5A power supply should be used to power the shield
    - Gyroscope pins connectoin to the arduino

 


# Running the code
 - run the LabView project into your Arduino