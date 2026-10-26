# Lab 6
## Task 1
### Circuit Explanation
An external LED was connected to digital pin 12 of the Arduino Uno using a breadboard. A 330 ohm resister was connected in series with the LED to limit the current and protect it from damage. The positive termainal (anode) of the LED was connected to ground (GND). This circuit allows the Arduino to control the LED by sending HIGH and LOW signals through pin 12.
### Code Explanation
The Arduino program uses the setup() function to configure digital pin 12 as an output using pinMode(12, OUTPUT). In the loop() function, digitalWrite(12, HIGH) turns the LED on, and delay(1000) keeps it on for one second. Next, digitalWrite(12, LOW) turns the LED off, followed by another one-second delay. Since the loop() function repeats continously, the LED keeps blinking with equal on and off intervals.
## Task 2
### Circuit Explanation
Two external LEDs were connected to the Arduino Uno through a breadboard. The first LED was connected to digital pin 12, while the second LED was connected to digital pin 11. Each LED had its own 330 ohm resistor connected in series to limit the current and prevent damage. The negative terminals of both LEDs were connected to ground (GND). By using two separate digital output pins, the Arduino can control each LED individually.
### Code Explanation
The program begins by configuring digital pins 12 and 11 as outputs in the setup() function. Inside the loop() function, the first LED connected to pin 12 is turned on using digitalWrite(12, HIGH) and remains on for one second. It is then turned off using digitalWrite(12, LOW) for another second. Using the same method, the second LED connected to pin 11 is turned on for one second and then turned off for one second. This sequence repeats continously, allowing the LEDs to blink one after another.