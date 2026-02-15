# Smart Fan Controller System

An intelligent temperature-based fan speed control system built using Arduino.  
The system automatically adjusts fan speed based on environmental temperature.

---

## Overview

The Smart Fan Controller is designed to optimize cooling efficiency by adjusting fan speed dynamically according to temperature readings.

This project demonstrates embedded control systems, sensor integration, and automation logic.

---

## Features

- Automatic fan speed control
- Temperature-based regulation
- Energy-efficient operation
- Real-time monitoring
- Proteus simulation included
- HEX file available for deployment

---

## Hardware Components

- Arduino Uno
- Temperature Sensor (LM35 / DHT compatible)
- DC Fan
- Transistor or MOSFET driver circuit
- Power Supply

---

## Software

- Arduino IDE (.ino source included)
- Proteus simulation project
- Compiled HEX file included

---

## Project Structure

```
Smart-Fan/
/
/// firmware/
/ /// smart_fan.ino
/
/// simulation/
/ /// proteus-project.pdsprj
/
/// images/
    /// simulation.png
```

---

## Working Principle

1. The temperature sensor reads ambient temperature.
2. Arduino processes the data.
3. Based on predefined thresholds:
   - Low temperature ? Fan OFF / Low speed
   - Medium temperature ? Medium speed
   - High temperature ? Maximum speed
4. Speed control is achieved via PWM signal.

---

## Future Improvements

- LCD display integration
- Mobile app control
- IoT cloud monitoring
- Adaptive speed control algorithm

---

## License

This project is licensed under the MIT License.

---

## 👥 Authors

Developed collaboratively by:

- Soheil Ahmadi
- Omid Menbari
  
Open-source project for learning and development purposes.
