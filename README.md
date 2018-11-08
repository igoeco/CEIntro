# Computer Engineering - An Introduction
This repository will hold the Code accompanying my text, _Computer Engineering - An Introduction_. The text is free and will be released in three stages which correspond to the three parts of the book:
* Part I:  [Mathematical Foundations of Computing](https://drive.google.com/file/d/1bx0hrVCwrIqkuPFILVPWYCFzuypxcZ0b/view?usp=sharing)
* Part II: Instruction Set Architecture (ISA)
* Part III: High-Level Abstractions

Part I of the book covers the foundations of computing, the math, the digital circuitry combining logic gates, memory, computation models like Finite State Machines and Turing Machines. The goal is to present the buidling blocks that a computer is made of. Part II covers the blueprint (ISA) of a computer and the means to program it in assembly language. The specific ISA used is the [ARM Cortex M0](https://en.wikipedia.org/wiki/ARM_Cortex-M) realized on the [BBC Microbit](https://microbit.org/).  Part III deals with raising the level of abstraction from low-level assembly language to a higher-level C programming language. This allows us to operate with higher-level abstractions dealing in algorithms and data-structures.


## BBC Microbit
The BBC Microbit is a tiny computer that is more appropriately refered to as a _microcontroller_. Microcontrollers have all the same elements that go into a full-fledged computer but they are designed to be fully customizable in terms of the input/output devices they interface with. A computer is simply a customized instance of a microcontroller with  pre-packaged input (say keyboard, mouse, touchscreen etc.), output (say display, audio etc.) and input+output (say, wifi, bluetooth etc.) devices.

<img src="https://github.com/igoeco/CEIntro/blob/master/images/Microbit-Pins.png" alt="BBC Microbit" width="200"/>

As seen in the image above, the microbit allows interfacing through its pins, which can be used to connect external switches, LEDs, displays, motors, speakers, microphones etc. It also has a few builtin (internal) devices, two switches, 5x5 red LEDs, an accelerometer and, networking using Bluetooth and radio.

There are excellent resources to program this microcontroller in languages like python, javascript and Swift. The traget of my text is a budding engineer and not a casual programmer. I want you to know a computer from the bottom up with no shortcuts to the top. That means, programming the machine at the lowest level possible. The lowest-level is really machine code but we work in assembly language, which allows us to express operations symbollically instead of the burdensome machine code.







