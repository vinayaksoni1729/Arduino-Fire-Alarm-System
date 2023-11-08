# Arduino Fire Alarm System

This is an Arduino project that implements a fire alarm system using a flame sensor. When a fire or flame is detected, it triggers an alarm (buzzer) and activates an LED to alert the user. The code provided in this repository includes an Arduino sketch for interfacing with the flame sensor and controlling the alarm and LED.

## Components

- Arduino board (e.g., Arduino Uno)
- Flame sensor
- Buzzer
- LED
- Jumper wires

## Diagram
![image](https://github.com/vinayaksoni1729/Arduino-Fire-Alarm-System/assets/113187290/d85197cb-05cc-4321-b213-2982f30819e3)


## Wiring

Make the following connections between the Arduino and the components:

- Connect the buzzer to Arduino pin 8.
- Connect the LED to Arduino pin 7.
- Connect the flame sensor to Arduino pin 4.

## Arduino Sketch

The Arduino sketch provided in this repository is responsible for detecting fires or flames using the flame sensor and taking appropriate actions. Here's a brief overview of the key components:

- `setup()`: Initializes the Serial communication and configures the pins for the buzzer, LED, and flame sensor.
- `loop()`: Repeatedly reads the digital signal from the flame sensor.
- If a fire or flame is detected (flame_sensor = 1), the system triggers an alarm (buzzer) and activates an LED to alert the user.
- If no fire or flame is detected (flame_sensor = 0), the system remains in a normal state.

The code reads the flame sensor's digital signal to detect the presence of a fire.

## Usage

1. Upload the Arduino sketch to your Arduino board using the Arduino IDE.
2. Make sure the circuit connections are correctly set up as described in the wiring section.
3. Power up the Arduino board.
4. Open the Serial Monitor in the Arduino IDE (Ctrl + Shift + M) to view the system's status messages.

The buzzer and LED will activate when a fire is detected, providing an immediate alert. Adjust the delay values in the code to control the duration of the alerts..

Feel free to modify and adapt this code for your specific fire alarm system applications.

Stay safe!
