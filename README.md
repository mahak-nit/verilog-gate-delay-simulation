# Verilog Gate Delay Simulation

Overview:
This project demonstrates propagation delays in Verilog using continuous assignments and basic logic gates.

Design Description:
The design uses two logic operations:
* AND gate: 'temp = a & b' with a delay of 2 time units.
* NOT gate: 'y = ~temp' with a delay of 4 time units.

The inputs 'a' and 'b' are initially set to 0. After 5 time units, both inputs change to 1.

Tools Used:
- Verilog HDL
- Icarus Verilog
- EDA Playground
- EPWave

Key Concepts:
- Continuous assignments
- Gate propagation delay
- '$monitor' for displaying signal values
- '$dumpfile' and '$dumpvars' for waveform generation
- Simulation and waveform analysis

Expected Results:
- At time 0, both inputs are 0.
- At time 5, both inputs change to 1.
- After 2 time units, the AND gate output 'temp' becomes 1.
- After another 4 time units, the NOT gate output 'y' becomes 0.

How to Run:
1. Open EDA Playground.
2. Select Icarus Verilog as the simulator.
3. Paste the Verilog code into the design editor.
4. Enable the EPWave option.
5. Click Run and inspect the waveform.

Learning Outcome:
This project helped me understand propagation delays, continuous assignments, and waveform generation in Verilog.

