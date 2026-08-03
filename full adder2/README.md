# Full Adder using Verilog

## Project Overview
This project implements a **1-bit Full Adder** using Verilog HDL.

A Full Adder adds three binary inputs:
- A
- B
- Cin (Carry Input)

It produces:
- Sum
- Cout (Carry Output)

## Truth Table

| A | B | Cin | Sum | Cout |
|---|---|-----|-----|------|
|0|0|0|0|0|
|0|0|1|1|0|
|0|1|0|1|0|
|0|1|1|0|1|
|1|0|0|1|0|
|1|0|1|0|1|
|1|1|0|0|1|
|1|1|1|1|1|

## Logic Equations

Sum = A ^ B ^ Cin

Carry = (A & B) | (B & Cin) | (A & Cin)

## Files

- full_adder.v
- full_adder_tb.v
- simulation_results.png

## Software Used

- ModelSim
- Vivado Simulator
- Icarus Verilog
- GTKWave

## Expected Output

The simulation verifies all possible input combinations of the Full Adder.

## Author

Your Name