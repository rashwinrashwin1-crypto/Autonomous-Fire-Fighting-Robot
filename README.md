# Autonomous Fire Fighting Robot

## About the Project

The Autonomous Fire Fighting Robot is an Arduino UNO based project designed to detect and respond to fire automatically. The main purpose of the project is to reduce the need for humans to directly approach fire-prone areas and to demonstrate a simple robotic system for fire detection and extinguishing.

The robot uses a flame sensor and temperature sensor to detect the presence of fire. Once fire is detected, the Arduino UNO processes the sensor information and controls the motors to move the robot towards the fire. A water pump is then used to spray water and help extinguish the fire.

## Components Used

The main components used in this project are:

* Arduino UNO
* Flame Sensor (KY-026)
* Temperature Sensor
* L298N Motor Driver
* BO/DC Motors
* Water Pump
* Water Tank
* Relay Module
* Rechargeable Li-ion Battery
* Robot Chassis

## Working

The robot continuously monitors its surroundings using the flame and temperature sensors. When a fire or high temperature is detected, the sensor sends the information to the Arduino UNO.

The Arduino processes the sensor input and controls the motor driver to move the robot towards the detected fire. When the robot reaches the fire area, the water pump is activated through the relay module. Water from the tank is sprayed towards the fire until the fire is controlled.

## Project Flow

```text
Fire Detection
      ↓
Flame / Temperature Sensor
      ↓
Arduino UNO
      ↓
Motor Driver
      ↓
Robot Movement
      ↓
Fire Location
      ↓
Relay + Water Pump
      ↓
Fire Extinguishing
```

## Software Used

The robot is programmed using **Arduino IDE** with **Embedded C / Arduino programming**.

## Project Structure

```text
Autonomous-Fire-Fighting-Robot/
│
├── Arduino_Code/
├── Circuit_Diagram/
├── Block_Diagram/
├── Images/
├── Report/
└── README.md
```

## Applications

This robot can be used as a basic model for fire detection and extinguishing in places where it may be difficult or unsafe for people to approach directly. It can also be used for learning and demonstrating robotics, embedded systems and sensor-based automation.

## Future Improvements

The robot can be improved by adding a camera for better fire detection, wireless or IoT control, obstacle detection, automatic navigation and more advanced fire detection methods.

## Conclusion

The Autonomous Fire Fighting Robot demonstrates how sensors, Arduino UNO, motors and a water pumping system can be combined to build a simple fire-fighting robot. The project provided practical experience in embedded programming, sensor interfacing, motor control and automation.
