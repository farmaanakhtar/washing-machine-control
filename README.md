# Washing Machine Control System - Prototype

## Overview
Microcontroller-based control system implementing automated washing machine cycle management with configurable wash programs.

## Project Achievement
🏆 4th Position at TechVision College Technical Event (2024)

## System Components

### Hardware
- Microcontroller (ATmega328P/Arduino)
- Motor control module (relay/MOSFET)
- Sensors: Water level sensor, temperature sensor
- User interface: Buttons/LCD display

### Software
- **Language:** Arduino C
- **Architecture:** State machine
- **Wash Cycles:** Configurable programs (cotton, delicate, heavy-duty, etc.)

## Wash Cycle Logic
The system implements a state machine:

1. **Idle State** → User selects wash program
2. **Pre-wash** → Water fill + detergent
3. **Main Wash** → Motor rotation + agitation
4. **Rinse** → Water drain + refill cycles
5. **Spin** → High-speed dehydration
6. **Complete** → Return to idle

## Configurable Parameters
- Water temperature
- Wash duration
- Spin speed
- Rinse cycles
- Drain intervals

## Features
✅ Multiple wash programs
✅ Automatic water level control
✅ Temperature monitoring
✅ Motor speed regulation
✅ Safety interlocks (door detection)
✅ Status display/LEDs

## Implementation
- Modular code structure
- Interrupt-driven sensor reading
- PWM for motor speed control
- State machine for cycle management

## Results
✅ Successfully implemented all wash cycles
✅ Automatic water management
✅ Real-world appliance control
✅ User-friendly interface
✅ Recognized at TechVision Technical Event

## Skills Demonstrated
- Embedded systems design
- Hardware-software integration
- Real-time control systems
- Sensor interfacing
- State machine implementation

## Author
Farmaan Akhtar
