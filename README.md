# ESP32-and-PIR-LDR-sensor-

In this project we focus to turn on the LED When there is no light but there is movement by using ESP32 microcontroller . 

Components :

ESP32 microcontroller 

PIR (Passive Infrared) motion sensor

LDR (Light Dependent Resistor) or photoresistor

LED

Resistors

Breadboard and connecting wires .


we Connect the LDR in a voltage divider configuration with a resistor to an analog input pin on the ESP32. 

This setup will allow the ESP32 to read the ambient light level.

Connect the PIR sensor to a digital input pin on the ESP32. 

The PIR sensor will detect motion and output a high signal when motion is detected.

Connect the LED to a digital output pin on the ESP32 through a current-limiting resistor. 


The system was tested under various lighting conditions and motion scenarios. The LED successfully turned on when the ambient light level was below the set threshold and motion was detected by the PIR sensor. This demonstrates the system's ability to operate effectively as intended.


![photo_5859567175935837470_y](https://github.com/user-attachments/assets/f7cb68b3-3e6c-46df-8f58-85ff3e715e18)
here there was light and no motion , so the LDR  turn off
