# Door Alarm (Ultrasonic + Buzzer)

Arduino sketch that watches a door with an HC-SR04 ultrasonic sensor and sounds a buzzer when something gets close.

## How it works
- Triggers the ultrasonic sensor on a loop and times the echo to compute distance.
- If the measured distance is 10 cm or less, the buzzer is driven HIGH and "Door Open" is logged over serial; otherwise the buzzer stays off and "Door closed" is logged.

## Hardware
- Arduino Uno/Nano
- HC-SR04 ultrasonic sensor (trigger on pin 2, echo on pin 3)
- Buzzer on pin 10

College project, 2019–2021.
