# 🚦 Traffic Light Controller using Verilog HDL

This project implements a **Finite State Machine (FSM)** based Traffic Light Controller for a four-road intersection using **Verilog HDL**.  
The controller manages traffic flow for:

- Main Road 1 (M1)
- Main Road 2 (M2)
- Main Turn (MT)
- Side Road (S)

---

## 🔧 Design Overview

- FSM Type: **Moore Machine**
- Number of States: **6 (S1–S6)**
- Timing Control: **Synchronous counter**
- Reset Type: **Asynchronous reset**
- Clock: **1-second simulated clock**

Each state represents a unique traffic condition, and the controller transitions between states based on a programmable timer.

---

## 🧠 State Description

| State | Description |
|------|-------------|
| S1 | Main roads green |
| S2 | Transition (yellow) |
| S3 | Main turn green |
| S4 | Transition (yellow) |
| S5 | Side road green |
| S6 | Transition (yellow) |

---

## 🧪 Verification

- Behavioral simulation using **Vivado Simulator**
- Verified signals:
  - `ps[2:0]` – present state
  - `count[3:0]` – timing counter
  - Traffic light outputs for all roads
- RTL and Synthesized schematic analysis performed

---

## 🛠 Tools Used

- Verilog HDL
- Xilinx Vivado
- FSM design methodology
- Behavioral Simulation

---

## 👨‍💻 Author

**Samy**  
Electronics & Communication Engineering  
Interested in VLSI, FPGA, and Digital Design


