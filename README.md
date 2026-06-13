# 1-Bit Full Adder in Verilog HDL

## 📌 Project Overview

This project implements a **1-bit Full Adder** using **Verilog HDL** and verifies its functionality through simulation in **Xilinx Vivado**.

A Full Adder is a combinational logic circuit that adds three 1-bit binary inputs (`A`, `B`, and `Cin`) and produces two outputs:

* **Sum**
* **Carry**

## 📂 Project Files

* `full_adder02.v` – Verilog implementation of the Full Adder
* `stimulation.v` – Testbench for simulation
* `README.md` – Project documentation

## 🧮 Logic Equations

```text
Sum   = A ⊕ B ⊕ Cin
Carry = (A & B) | (B & Cin) | (A & Cin)
```

## 📋 Truth Table

| A | B | Cin | Sum | Carry |
| - | - | --- | --- | ----- |
| 0 | 0 | 0   | 0   | 0     |
| 0 | 0 | 1   | 1   | 0     |
| 0 | 1 | 0   | 1   | 0     |
| 0 | 1 | 1   | 0   | 1     |
| 1 | 0 | 0   | 1   | 0     |
| 1 | 0 | 1   | 0   | 1     |
| 1 | 1 | 0   | 0   | 1     |
| 1 | 1 | 1   | 1   | 1     |

## ▶️ Simulation

The testbench applies all possible input combinations and verifies that the generated `Sum` and `Carry` outputs match the expected Full Adder truth table.

## 🛠️ Tools Used

* Verilog HDL
* Xilinx Vivado
* Behavioral Simulation

## 🎯 Learning Outcomes

* Understanding combinational logic circuits
* Writing Verilog modules and testbenches
* Performing behavioral simulation in Vivado
* Verifying digital designs using waveform analysis

## 👨‍💻 Author

**Neeraj Yadav**
M.Tech (Research), IIT Dharwad
Interested in VLSI Design, Verilog HDL, and Semiconductor Devices.
