# Paper Puppets

## In this Report

To submit your lab, clone [this repository](https://github.com/FAR-Lab/IDD-Fa18-Lab4). You'll need to describe your design, include a video of your paper display in operation, and upload any code you wrote to make it move.

## Part A. Actuating DC motors

[video](https://youtu.be/0XEY083GI4s)
## Part B. Actuating Servo motors

### Part 1. Connect the Servo to your breadboard

**a. Which color wires correspond to power, ground and signal?**  
Red = power, brown = ground, orange = signal.

### Part 2. Connect the Servo to your Arduino

**a. Which Arduino pin should the signal line of the servo be attached to?**  
PIN 9

**b. What aspects of the Servo code control angle or speed?**  
for (pos = 0; pos <= 180; pos += 1) { // goes from 0 degrees to 180 degrees
    // in steps of 1 degree
    myservo.write(pos);              // tell servo to go to position in variable 'pos'
	delay(15);                       // waits 15ms for the servo to reach the position
}

## Part C. Integrating input and output
[video](https://youtu.be/SVad7VHK_-4)
## Part D. Paper puppet

**a. Make a video of your proto puppet.**
[video](https://youtu.be/h8rLcsH2-4A)

## Part E. Make it your own

 a nodding-head dog
 [video](https://youtu.be/hXGP5REydUI)
