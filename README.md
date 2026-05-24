# VLSI Design Internship - Task 2

## Introduction
This repository contains Verilog HDL implementations of basic combinational circuits using Xilinx ISE Design Suite.  
The project includes Verilog coding, testbench creation, simulation, waveform analysis, and GitHub documentation.

---

# Objectives

- Learn Verilog HDL fundamentals
- Understand RTL design concepts
- Implement combinational logic circuits
- Write Verilog testbenches
- Perform behavioral simulation
- Analyze waveform outputs

---

# Implemented Circuits

- AND Gate
- OR Gate
- NOT Gate
- NAND Gate
- NOR Gate
- XOR Gate
- Half Adder
- Full Adder

---

# Truth Table (Half Adder)

| A | B | Sum | Carry |
|---|---|---|---|
| 0 | 0 | 0 | 0 |
| 0 | 1 | 1 | 0 |
| 1 | 0 | 1 | 0 |
| 1 | 1 | 0 | 1 |

---

# Sample Verilog Code

```verilog
module half_adder(
    input a,
    input b,
    output sum,
    output carry
);

assign sum = a ^ b;
assign carry = a & b;

endmodule
```

---

# Tools Used

- Verilog HDL
- Xilinx ISE Design Suite
- ISim Simulator
- GitHub

---

# Simulation

Behavioral simulations were performed using ISim Simulator in Xilinx ISE Design Suite.  
Waveforms were analyzed to verify correct output functionality.

# Folder Structure

```text
VLSI-Design-Internship-Task2/
│
├── Verilog_Codes/
│   ├── and_gate.v
│   ├── or_gate.v
│   ├── xor_gate.v
│   ├── half_adder.v
│   └── full_adder.v
│
├── Testbenches/
│   ├── and_gate_tb.v
│   └── full_adder_tb.v
│
├── Screenshots/
│   ├── and_gate_waveform.png
│   ├── half_adder_output.png
│   └── full_adder_waveform.png
│
└── README.md
```

---

# Learning Outcomes

- Learned Verilog HDL syntax and module design
- Understood combinational circuit implementation
- Gained experience in testbench writing
- Performed waveform analysis and simulation
- Improved GitHub project documentation skills

---

# Conclusion

This task provided practical exposure to digital logic design and Verilog HDL implementation.  
The project improved understanding of RTL design flow, simulation techniques, and waveform verification used in VLSI front-end design.

---

# Author

**Aparna Marisetty**
