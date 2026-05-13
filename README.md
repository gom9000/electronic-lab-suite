# Electronic Lab Suite
A set of custom-built instruments for the electronics workbench, covering power supply, component characterization, and load testing.

The suite is an ongoing project aimed at creating a comprehensive ecosystem of reliable, home-made tools for the electronics workbench. New instruments are developed starting from documented laboratory experiences to ensure maximum reliability and empirical validation.


## Suite Tools

### **[Multi Out Low-Power Supply Unit](https://github.com/gom9000/mopsu)**
**Type**: Power Supply | **Complexity**: Low | **Status**: Completed

A versatile, multi-rail linear low-power supply unit designed to power bench prototypes

- **Key Features**:
    - **Quad Output Rails**: Dedicated $3.3V$, $5V$, $9V$, and $12V$ regulated lines.
    - **Current Capacity**: Supports up to $500mA$ combined for $3.3V/5V$ rails and $250mA$ combined for $9V/12V$ rails.
    - **Linear Stability**: Uses standard $78xx$ series regulators and high-capacity filtering ($10000\mu F$) for low-ripple output.


### **[Diode Tester](https://github.com/gom9000/diode-tester)**
**Type**: Component Tester | **Complexity**: Low/Mid | **Status**: Testing

Measure the forward voltage drop ($V_f$) of diodes or the working voltage of Zener diodes under controlled conditions.

- **Key Features**:
    - **Selectable Constant Current**: Calibrated steps ($1mA, 2mA, 5mA, 10mA, 20mA, 30mA$) via rotary switch.
    - **High Voltage Range**: Supports supply voltages up to $30VDC$, allowing characterization of a wide range of Zener diodes.


### **Dummy Load for Low-Power PSU *(coming soon)***
**Type**: Active Load | **Complexity**: Mid | **Status**: In Development

A Constant Current (CC) load for PSU stress testing.

- **Key Features**:
    - **CC Mode**: Adjustable current from $0A$ to $1A$ via potentiometer.
    - **Thermal Safety**: Designed to handle up to $20W$ continuous dissipation.
    - **Wide Input Range**: Stable regulation from $1.5V$ up to $30V$.


## About
**Author**: Alessandro Fraschetti (gom9000).