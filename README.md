# Arduino-Light-Following-robot-car
Hey there, here in this article, I’m going to guide you to make an Arduino Light Following Robot. This is very easy to make (for beginners)

WHY ARDUINO UNO

Here in this project, I have made an Arduino Based Light Tracking Robot. I have used Arduino UNO as a Brain of this robot. I have enclosed an Arduino Code with this article which will help you to instruct the robot to follow the light source and move towards it.

WHY L293D MOTOR DRIVER SHIELD

I have used the L293d motor driver module to control the speed of the motor. There are several motor drivers available on the market but I personally like this one because this is easy to install with Arduino UNO, has 4 individual ports for 4 motors, and also there are many extra extended ports like 5v pins, GND pins, and analog pins, etc.

WHY LDR SENSOR MODULE

As it's a Light tracking robot so, our basic requirement is to track the light, right? and I have found LDR is the best solution for this. But we can't connect the LDR resistor directly with the Arduino or the motor driver. We need to make a compatible circuit for that, and in this state, I have found my solution on LDR sensor Module which is very low in price and also very easy to connect with the Arduino board.

Before starting let’s see first What you will learn from this instructable:
· Making the right hardware selection for your project depending on its functionalities.

· Prepare the circuit diagram to connect all the chosen components.

· Assemble all the project parts (mechanical and electronic assembly).

· Finally designing your own ARDUINO-based Light Tracking Robot.


Arduino Coding
Now I had to upload the code to the Arduino UNO.So I have attached the USB cable that comes with the Arduino UNO board and follows the steps mentioned below

· Open Arduino IDE on your PC

· Connect ARDUINO with PC via USB Cable

· Go to Tools > manage libraries > Search for AF Motor driver and download

· Go to Tools > Board > and select Arduino\Genuino UNO

· Go to Tools > Port > Select proper COM port

· Now Verify the code and then upload it

***Please don’t forget to remove/detach remove the yellow jumper cap from the motor driver before uploading the sketch/code. Re-Connect it after the code has been uploaded successfully.
