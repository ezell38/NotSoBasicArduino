# NotSoBasicArduino
 The follwing files are my second foray into Arduino
 
 
## Table of Contents
* [Table of Contents](#TableOfContents)
* [LED_Fade](#LED_Fade)
* [HelloFunctions](#HelloFunctions)
* [NewPing](#NewPing)
---

## LED_Fade

### Description & Code
Making a LED fade in and out for LED blink revisited assignment

### Code

 pinMode(led, OUTPUT);
}
// the loop routine runs over and over again forever:
void loop() {
 // set the brightness of pin 9:
 analogWrite(led, brightness);
 // change the brightness for next time through the loop:
 brightness = brightness + fadeAmount;
 // reverse the direction of the fading at the ends of the fade:
 if (brightness == 0 || brightness == 255) {
 fadeAmount = -fadeAmount ;
 }
 // wait for 30 milliseconds to see the dimming effect
 delay(30);      

I used the code that was already in the arduino examples and then used the wiring from the sparkfun blink tutorial. 

### Evidence
https://create.arduino.cc/editor/ezell38/cecbf522-9406-4b12-b7ff-cabeef84b5f1

### Images



### Reflection
This assignment was relitivly easy after you learned how to set up the wiring. 

## HelloFunctions

### Description & Code
Description goes here

Here's how you make code look like code:

```C++
Code goes here
```
Talk about how the code works, here....

### Evidence
link goes here

### Images
draw it yourself, take a picture, make a fritzing, whatever you want to EFFECTIVELY communicate how its put together.

### Reflection

## NewPing

### Description & Code
Description goes here

Here's how you make code look like code:

```C++
Code goes here
```
Talk about how the code works, here....

### Evidence
link goes here

### Images
draw it yourself, take a picture, make a fritzing, whatever you want to EFFECTIVELY communicate how its put together.

### Reflection

