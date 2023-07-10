# obstacle-avoiding-car

This project involves the design and implementation of an intelligent obstacle-avoiding robot 
car. The objective of this project is to implement a robot car, which while moving should 
have the ability to detect obstacles in its path and change direction where obstacles are 
present without any form of external influence. The new direction to be taken to avoid 
collision is the direction that has the most distance between the obstacle and the sensor and 
this is determined by the robot based on sensor inputs. This implementation was done using 
an ultrasonic wave sensor/ ir sensor, which measures distance by sending pulses. Also, the 
movement of the servo motor (for sensor movement) and the DC motors (for wheel 
movement) are controlled by the motor driver shield in order to enable the obstacle avoidance 
function. The commands are sent to the Arduino microcontroller chip which serves as the 
main control of the robot car, as it controls the sensor and car movement. The implemented 
robot car was able to successfully detect and avoid obstacles within the line of sight of the 
Ultrasonic sensor used.
