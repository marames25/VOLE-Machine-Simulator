# VOLE Machine Simulator

A C++ simulation of a simplified computer system that reads instructions, stores data in memory, and executes a basic machine cycle.

## Description
VOLE Machine Simulator models a simplified computer with components such as ALU, CPU, control unit, memory, and register systems.

## Features
- reads machine instructions
- executes instructions in full or step-by-step mode
- displays final memory state
- displays final register state
- object-oriented machine design
- console-based simulator

## Technologies Used
- C++
- object-oriented programming
- standard C++ library

## Prerequisites
- C++ compiler
- terminal or IDE

## Installation
```bash
g++ main.cpp Machine.cpp -o main
```

## How to Run
```bash
./main
```

On Windows:
```powershell
.\main.exe
```

## Project Structure
- `main.cpp`
- `Machine.h`
- `Machine.cpp`
- `CPU.h`
- `CPU.cpp`
- `CU.h`
- `CU.cpp`
- `ALU.h`
- `ALU.cpp`
- `Memory.h`
- `Memory.cpp`
- `Register.h`
- `Register.cpp`

## Notes
This is a console simulation project that demonstrates a simplified machine model and OOP design for educational purposes.
