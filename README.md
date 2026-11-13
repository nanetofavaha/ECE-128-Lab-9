# ECE-128-Lab-9: ROM and RAM

## Description

This lab focuses on designing and simulating Random Access Memory (RAM) and Read-Only Memory (ROM) using Verilog. The RAM stores 8-bit data across eight memory locations and supports reading and writing operations. The ROM stores 4-bit data across eight memory locations and retrieves predetermined values based on the selected address. Both designs were tested using behavioral simulations in Vivado

## Simulation

1. Open the project in Vivado
2. Add the Verilog source code and corresponding testbench files
3. Add the memory text files for the file-based implementations
4. Set the appropriate testbench as the simulation top module
5. Run Behavioral Simulation
6. Observe the waveforms to verify the RAM read/write operations and ROM data outputs

## FPGA Implementation

The designs were synthesized in Vivado to examine hardware resource utilization but were not tested on a physical FPGA board

To implement either design on an FPGA:

1. Set the RAM or ROM module as the top module
2. Add an appropriate constraints file and configure the FPGA inputs and outputs
3. Run Synthesis and Implementation
4. Generate the bitstream and program the FPGA board

## Results

The RAM simulation demonstrated successful writing and reading of data across the tested memory locations. The ROM simulation showed the expected data outputs for the selected addresses

The RAM utilized 25 slice LUTs and 72 slice registers, while the ROM utilized 2 slice LUTs
