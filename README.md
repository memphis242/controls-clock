# The Controls Clock
Wouldn't it be nice to have a little device at your desk that allows you to _visually_ and _quickly_ brush up on PID or observer tuning?

That is the need that I seek to address with this project. There are of course many ways that this can be done, but none seem quite as fun, interesting, and quick as a device like this!

The basic idea is this box-shaped device has a hand that moves like a clock's hand. You can configure the hand to behave like the hour, minute, or second hand of a typical analog clock, _or_ you can have it simply track a set angular position, like a servomotor. Most importantly, the hand moves according to the controls that _you_ set! You can have it in PID control mode (where you set the respective gains) or Full-State Feedback with an Observer (FSF+O) mode, where you set the relevant matrices and how much the observer's output is weighted compared to the pure sensor feedback. All these parameters are fully tunable, and you can see how the controls you set behave right away!

It can in fact go even further.
- The exact system parameters are displayed at the back of the device (hand mass, rotational inertia, gear ratios, motor inertia, motor torque constant, etc.). In FSF+O, the default system model is set with these in mind. _You can change these_.
- If enabled, noise can be introduced internally in software _on top_ of the sensor’s readings.
- If enabled, uncertainty can be introduced internally in software for the system's parameters, with each session going with slightly different values of the system's parameters.

I hope that all those I give this device to enjoy it thoroughly and find it useful.

# Device Demo
TODO

# Project Status / History
This project is in its initial development phase.

# Table of Contents
TODO

# Usage Instructions
TODO

# How Can I Get This?
TODO

# Repository Walk-Through
TODO

# Development Tech Used
### Hardware
TODO

### Software
TODO

# Detailed Documentation
TODO

# Contributing Guidelines
TODO

# License
TODO

# Acknowledgements
Credit where credit is due!

## Original Video Inspiration
I have to give credit to what originally inspired me to do this. Here's a link to the video that gave birth to this idea: [PID demo - Horizon 4 electronics](https://www.youtube.com/watch?v=qKy98Cbcltw&ab_channel=Horizon4electronics).  
[![image](https://github.com/memphis242/pid-tune-demo/assets/25826895/81d8d294-14fc-476c-aa16-9d758c547fcf)](https://www.youtube.com/watch?v=qKy98Cbcltw&ab_channel=Horizon4electronics)
