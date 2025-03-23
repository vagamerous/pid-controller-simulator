# PID Controller Simulation

This repository contains a simple Python simulation of a PID (Proportional-Integral-Derivative) controller applied to a first-order system. The goal is to demonstrate how a PID controller can regulate system behavior, specifically for automation and control applications.

## Features
- Models a first-order system with a transfer function.
- Implements a PID controller using adjustable parameters.
- Simulates step response to visualize system behavior.
- Plots system output to analyze performance.

## Prerequisites
Ensure you have Python installed along with the required libraries:
```bash
pip install numpy scipy matplotlib control
```

## Usage
Run the script to simulate the system response with the PID controller:
```bash
python pid_simulation.py
```

## Adjusting Parameters
You can modify the PID gains to observe their effects:
```python
Kp = 2.0  # Proportional gain
Ki = 0.1  # Integral gain
Kd = 1.0  # Derivative gain
```
Try different values to see how the system reacts.

## Example Output
The script generates a plot showing the system's response over time. Proper tuning of the PID controller ensures stability and minimal overshoot.

## License
This project is open-source and available under the MIT License.

