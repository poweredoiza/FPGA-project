# FPGA-project
logic synthesis flow optimization for FPGA fab
## Project Overview

This project implements a prototype **automatic logic synthesis flow** for FPGA fabrics using VHDL as input.  
The goal is to convert VHDL circuits into FPGA-compatible logic blocks (LUTs and flip-flops) while performing basic optimizations for area and performance.  

The synthesis flow includes: parsing supported VHDL constructs, building an internal logic representation, performing simple optimizations, mapping logic to FPGA LUTs, and generating a netlist with performance metrics.  

This repository will serve as the central documentation and implementation space for the project as it evolves.

