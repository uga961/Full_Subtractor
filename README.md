# CMOS Full Subtractor Project

## Overview

This project involves designing, simulating, and analyzing a **CMOS Full Subtractor** using **Cadence Virtuoso**. The Full Subtractor is a fundamental combinational circuit used for binary subtraction, generating a **difference (D)** and a **borrow-out (Bout)** output while considering a **borrow-in (Bin)** input.

## Software & Tools Used

- **Cadence Virtuoso** (for schematic capture, layout, and simulation)
- **Assura** (for DRC and LVS verification)
- **Analog Design Environment (ADE)** (for waveform analysis)

## Project Workflow

### Schematic Design

- Designed using **Virtuoso Schematic Editor**.
- Constructed using **NAND, NOR, and NOT gates** from a custom-built library.
- Verified through **Transient analysis**.

### Layout Design

- Created using **Virtuoso Layout Editor**.
- Optimized for **area efficiency** and minimal parasitics.
- Design Rule Check (**DRC**) performed for layout validation.

## Technical Specifications

- **Technology Node**: 90nm (as per design constraints)
- **Supply Voltage (VDD)**: 1V
- **Logic Operation**: Full Subtractor (D = A ⊕ B ⊕ Bin, Bout = A'Bin + B'Bin + A'B)

## Results & Observations

- **Schematic Simulation**: Verified correct Full Subtractor functionality.
- **Layout Optimization**: Ensured minimal area and **DRC compliance**.
- **Post-Layout Simulation**: Observed deviations due to parasitic capacitance and resistance.

## Reference Images

- **Full\_Subtractor\_Schematic**

  ![Full_Sub_Schematic](https://github.com/user-attachments/assets/7e5308d2-323b-41de-b3c6-849de91f52c7)

- **Full\_Subtractor\_ADE**

  ![Full_Sub_ADE](https://github.com/user-attachments/assets/9be9c610-b37e-4ad9-b739-07a66e587618)


## Caution

- **Note:** For testing, users need to **import the symbol via instance** and check for valid inputs and outputs.

- This project is designed using **custom NAND, NOR, and NOT gates** from a self-built library.

- **Copying this file alone will not work**—users need to **add the NAND, NOR, and NOT gates** to their own library first to use it correctly.

---

*This project belongs to me and is intended for educational and research purposes only. It should not be used directly for other purposes without permission.*

