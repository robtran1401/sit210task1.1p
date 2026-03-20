# sit210task1.1p
Task 1.1P SIT210
# Task1.1P - Switching ON Lights
## System Description
This system is designed for a smart elderly care home. When Linda arrives home and presses a push button, the porch light and hallway light turn on automatically. The porch light stays on for 30 seconds and the hallway light stays on for 60 seconds. This helps improve safety and convenience when entering the house at night.

## Components Used
- Arduino Nano 33 IoT
- 2 LEDs
- 2 resistors
- 1 push button
- Breadboard
- Jumper wires

## How the Program Works
The program waits for Linda to press the push button. When the button is pressed, both LEDs are turned on. The porch LED is programmed to stay on for 30 seconds, while the hallway LED stays on for 60 seconds.

## Modular Programming Approach
The program is divided into smaller functions to improve readability and usability:
- `setupPins()` sets up all input and output pins.
- `isButtonPressed()` checks whether the button is pressed.
- `turnOnPorchLight()` switches on the porch light and records its start time.
- `turnOnHallwayLight()` switches on the hallway light and records its start time.
- `updatePorchLight()` checks whether the porch light should turn off after 30 seconds.
- `updateHallwayLight()` checks whether the hallway light should turn off after 60 seconds.
