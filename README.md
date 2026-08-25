# 🚗 Autonomous Obstacle-Avoiding Car

## 🚗 Overview

An Arduino-based autonomous robot car capable of detecting obstacles using an ultrasonic sensor and automatically changing its direction to avoid collisions.

---

## ✨ Features

* Autonomous obstacle detection
* Real-time distance measurement
* Automatic left/right path selection
* Servo-based ultrasonic scanning
* Dual DC motor control
* Obstacle avoidance without manual intervention

---

## 🛠️ Components Used

* Arduino UNO
* HC-SR04 Ultrasonic Sensor
* SG90 Servo Motor
* L298N Motor Driver
* 2 DC Motors
* Robot Chassis
* Wheels
* 18650 Batteries
* Battery Holder
* Jumper Wires
* Switch

---

## ⚙️ Working Principle

1. The ultrasonic sensor continuously measures the distance in front of the car.
2. When an obstacle is detected within the predefined safe distance, the car stops.
3. The servo motor rotates the ultrasonic sensor to scan the left and right sides.
4. The Arduino compares the available distances.
5. The car turns toward the side with more free space.
6. The process repeats continuously while the car moves autonomously.

---

## 🔌 Connections

### 📡 HC-SR04 Ultrasonic Sensor

| HC-SR04 | Arduino UNO |
| ------- | ----------- |
| VCC     | 5V          |
| GND     | GND         |
| TRIG    | D13         |
| ECHO    | D12         |

### 🔄 SG90 Servo Motor

| Servo  | Arduino UNO |
| ------ | ----------- |
| Signal | D11         |
| VCC    | 5V          |
| GND    | GND         |

### ⚡ L298N Motor Driver

| L298N | Arduino UNO |
| ----- | ----------- |
| IN1   | D7          |
| IN2   | D6          |
| IN3   | D5          |
| IN4   | D4          |

---

## 💻 Software and Tools

* Arduino IDE
* Embedded C/C++
* Wokwi
* GitHub

---

## 🔄 Simulation and Testing

The project was initially tested and debugged using simulation before hardware implementation.

The simulation helped in testing:

* Ultrasonic sensor distance measurement
* Servo motor movement
* Left and right obstacle scanning
* Motor control logic
* Obstacle avoidance decision-making

The hardware prototype was then tested and debugged to ensure proper coordination between the ultrasonic sensor, servo motor, L298N motor driver, and DC motors.

---

## 🚀 Future Improvements

* Add Bluetooth control
* Improve obstacle detection accuracy
* Add object-following functionality
* Integrate machine learning for navigation
* Add GPS-based navigation
* Improve path-planning algorithms

---

## 📁 Project Structure

```text
Autonomous-Obstacle-Avoiding-Car/
│
├── README.md
│
├── Arduino_Code/
│   └── Autonomous_Obstacle_Avoiding_Car.ino
│
├── Circuit_Diagram/
│   └── circuit_diagram.png
│
├── Images/
│   ├── complete_car.jpg
│   ├── sensor_servo.jpg
│   └── hardware_setup.jpg
│
├── Simulation/
│   └── simulation_link.txt
│
└── Documentation/
    └── project_documentation.pdf
```

---

## 👥 Contributors

* Team Member 1 : Krishnapriya Singh 
* Team Member 2 : Ronak Chundawat
* Team Member 3 : Sanskriti Yadav

## 👩‍💻 Project Team

The project was developed collaboratively by students with an interest in robotics, embedded systems, and autonomous systems.

---

⭐ If you found this project interesting, consider giving the repository a star!

