# 🛒 Vending Machine using Verilog HDL

This project implements a simple vending machine using **Verilog HDL** and was simulated using **Xilinx Vivado**. The vending machine accepts coins and dispenses products based on the input amount.

---

## 📌 Project Overview

- 💡 Designed a vending machine that accepts coins of ₹1, ₹2, and ₹5.
- 🧃 Dispenses a product when the total amount matches or exceeds the product price.
- 🔄 Handles reset and change logic.
- 🧪 Simulated and verified using Vivado's behavioral simulation.

## 🧾 Features

- Accepts coin inputs (1, 2, 5)
- Tracks the total amount inserted
- Dispenses product when amount ≥ required
- Resets system after each transaction
- Displays status via output signals

  ## 🗂️ Folder Structure
vending-machine-verilog/
├── src/
│ └── vending_machine.v # Main Verilog module
├── testbench/
│ └── vending_tb.v # Testbench file
├── simulation/
│ └── vending_output.vcd (optional)
├── video/
│ └── output_demo.mp4 # Output video
└── README.md # Project documentation

# 🛠️ Tools Used

- **Vivado Design Suite 2025.1**
- **Windows/Linux**
- Simulation: Vivado Behavioral Simulation
- Optional: GTKWave for waveform viewing

---

