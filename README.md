# Line-Following-Robot
An autonomous line-following robot built with Arduino, IR sensors, and an L298N motor driver. Uses real-time IR feedback for line tracking and PWM-based motor control for smooth steering, powered by a LiFePO4 battery.

## How It Works
The robot uses an array of IR sensors to detect the line's position relative to the chassis by sensing contrast between the line and the surface. Based on sensor readings, the Arduino computes the required correction and sends PWM signals to the L298N motor driver, which controls the speed and direction of two DC motors — allowing the robot to steer left, right, or move straight to stay on the line.

## Components Used
- Arduino
- IR Sensor Array
- L298N Motor Driver
- 2x DC Motors
- LiFePO4 Battery
- Chassis, Wheels, Caster Wheel

## Key Features
- Real-time line tracking using IR feedback
- PWM-based motor speed control for smooth turns
- Stable power delivery via LiFePO4 battery
