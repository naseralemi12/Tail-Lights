# Turn signals with adaptive taillights

This project allows you to control the taillights of your bicycle with the Circuit Playground Express from Adafruit. The taillights automatically adjust their brightness depending on the ambient light, and can also be controlled to act as turn signals or brake lights. 

## Usage

To use the turn signals, press and hold button A for the left turn signal or button B for the right turn signal. The corresponding taillights will flash red in increments of 0.35 seconds. 

To use the brake lights, the sensor should be triggered by the brake string when the rider pulls the brake levers. This will turn on the red lights to signal that the rider is braking. 

To activate the hazard signal, toggle button B. The taillights will flash red and orange alternately with a delay of 0.35 seconds between each flash. 

## Code

The code for this project can be found in the `main.py` file. It uses the `adafruit_circuitplayground` library to interact with the Circuit Playground Express board. 


## Demo
<https://www.youtube.com/shorts/q2xEXhpJC2k>

![screenshot](./1%20(7).png)
![screenshot](./1%20(6).png)
![screenshot](./1%20(5).png)
![screenshot](./1%20(4).png)
![screenshot](./1%20(3).png)
![screenshot](./1%20(2).png)
![screenshot](./1%20(1).png)
