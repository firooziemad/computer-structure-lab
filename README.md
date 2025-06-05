# Computer Structure and Microprocessors Labs

## 📂 Repository Structure

- **`verilog/`**: Verilog source files for MIPS processor designs and digital hardware implementations.
- **`assembly/`**: MIPS Assembly code for testing processor implementations.
- **`pic32/`**: Code and documentation related to PIC32 microcontroller experiments.
- **`common/`**: Shared components, modules, and supporting files across different experiments.

## 🛠️ Tools and Technologies

- **ModelSim**: For simulation and functional verification of Verilog designs.
- **Xilinx Vivado**: For synthesis and implementation of Verilog modules.
- **Verilog**: Hardware description language for digital logic design.
- **MIPS Assembly**: For low-level programming and processor testing.
- **MPLAB X IDE**: For PIC32 microcontroller programming and debugging.

## 🚀 Project Overview

Contains Verilog and MIPS Assembly code developed for lab assignments in the Computer Structure and Microprocessors course. Includes hardware implementations and embedded software experiments focusing on processor architecture and microcontroller-based systems.

## 🔬 Lab Descriptions

- **8-bit Serial Multiplier**  
  Hardware implementation of an 8-bit serial multiplier using Verilog. Simulated to verify correctness.

- **IEEE-754 Floating-Point Adder**  
  Single-precision floating-point adder based on IEEE-754 standard, verified using ModelSim simulation.

- **Single-Cycle MIPS Processor**  
  Implementation of a single-cycle MIPS processor supporting:  
  - R-format instructions: `add`, `sub`, `addu`, `subu`, `and`, `or`, `xor`, `nor`, `slt`, `sltu`  
  - I-format instructions: `addi`, `addiu`, `slti`, `sltiu`, `andi`, `ori`, `xori`, `lui`, `beq`, `bne`, `lw`, `sw`

- **Multi-Cycle MIPS Processor**  
  Datapath and controller implementation of a multi-cycle MIPS processor in Verilog, tested with assembly programs.

- **PIC32 Microcontroller Experiments**  
  Introduction to PIC32 MX110F016B, including:  
  - Switch input and LED output with debouncing  
  - 7-segment display control  
  - Matrix keypad interfacing  
  - Interrupt handling (bonus)  
  - LCD initialization and a simple calculator implementation

## 👨‍💻 Supervisor

- **Dr. Mohammad Reza Movahedin**
