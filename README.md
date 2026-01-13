# DC/AC Inverter Control Simulation using MATLAB/Simulink

## Overview
This project demonstrates a simulation-based implementation of a single-phase DC/AC inverter control using MATLAB/Simulink. The focus is on understanding sinusoidal pulse width modulation (SPWM) and inverter output voltage behavior at signal level.

## Methodology
- A sinusoidal reference signal (50 Hz) is generated to represent the desired AC output.
- A high-frequency carrier signal is generated using a repeating sequence block.
- SPWM is implemented by comparing the reference and carrier signals using a relational operator.
- The PWM signal is scaled and biased to model a bipolar inverter output voltage (±200 V) assuming a 400 V DC input.
- Data-type conversion is applied to ensure correct numerical behavior during voltage scaling.

## Key Results
- Successful generation of SPWM gating signals.
- Bipolar inverter output voltage waveform with sinusoidal envelope.
- Stable simulation without numerical overflow warnings.

## Tools Used
- MATLAB
- Simulink

## Notes
This is a simulation-based academic project intended for learning and analysis of inverter control principles. No physical hardware implementation is included.
