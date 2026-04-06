# cpu-hw10
Implementation of a simplified Caltech10 CPU using ABEL hardware description language, including arithmetic logic, control flow, and memory access components.

# Overview
This project implements key components of a basic CPU architecture, including instruction handling, arithmetic operations, and program flow control. The design was developed and tested on CPLD hardware.

# Components
## Arithmetic Logic Unit (ALU)
Supports addition and subtraction using two’s complement arithmetic and generates flags such as Carry, Overflow, Zero, and Sign.
## Control Unit
Generates control signals to coordinate instruction execution and manage data flow between components.
## Program Access Unit
Handles instruction addressing, including direct addressing, offset branching, and return-from-subroutine (RTS) behavior.
## Data Access Unit
Manages data movement and memory interactions.
## CPU Integration
Combines all components into a functional system capable of executing instructions.

# Key Concepts
Two’s complement arithmetic
Boolean logic minimization
Combinational and sequential logic design
Instruction flow and control signals
Tools & Technologies
ABEL Hardware Description Language
CPLD hardware (for synthesis and testing)

# Notes
This project emphasizes low-level system design and the interaction between different hardware components in a CPU architecture.
