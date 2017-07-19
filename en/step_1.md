With the motor controller board connected to your Raspberry Pi, and Scratch 2 open, you can control the direction of your motors easily,

- The motor controller board is linked with pins 7, 8, 9 and 10. For the purposes of this guide, the right hand motor is connected to pins 7 and 8, and the left hand motor is connected to pins 9 and 10.

- To drive both motors forward, you need to send pins 7 and 9 high. Pins 8 and 10 need to be sent low.

- To drive both motors backward, you need to send pins 8 and 10 high, and pins 7 and 9 low.

- If you want to turn the motors in opposite directions (for turning a robot, for instance), you could send pins 7 and 10 high, and pins 8 and 9 low.

- To turn in the other direction, send pins 8 and 9 high, while pins 7 and 10 are sent low.
