# Experimenting the 28BYJ-48-Stepper-Motor and ULN2003 board

This simple project is the demonstration of controlling 28BYJ-48 stepper motor using the **Arduino** and the **ULN2003** boards. This stepper motor functions demonstrated here will further be used in the 4 DOF robotic arm project, and with this simplified version of the stepper motor control I am able to showcase how to turn the **degrees** into the **steps** that the motor understands

##  Project Overview

- **Microcontroller:** Arduino Uno (or compatible)
- **Motor:** 28BYJ-48 Stepper Motor
- **Driver:** ULN2003 Motor Driver Board
- **Library:** Stepper.h (built-in Arduino library)

##  How It Works

1. Arduino waits for text input from the **Serial Monitor**.
2. When the user types a command such as: **rotate 180 degrees**

The program:
- Extracts the numeric angle (positive or negative).
- Converts degrees into motor steps.
- Rotates the motor **clockwise** for positive angles and **counterclockwise** for negative angles. 

## 🔮 Future improvements
- Embedding the stepper motors into the robotic arm project 
- Add a simple GUI based control system for interacting with the commands to the system

# Author
**Darlene GANZA**
