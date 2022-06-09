# RISC-V-CPU-Core
This repo contains the codes which I implemented while completing the course "Building a RISC-V CPU Core"  offered by Linux Foundation through edx.
The processor has a support of base integer RV32I instruction format written in TL- Verilog on Makerchip platform.
<hr>

# RISC-V Overview
RISC-V (pronounced "risk-five") is an open standard instruction set architecture (ISA) based on established RISC principles.Unlike most other ISA designs, RISC-V is provided under open source licenses that do not require fees to use. RISC-V is also popular for it's simplicity and extensibility and infact RISC stands for Reduced Instruction Set Architecture.
It contains 32 registers and most instructions are read from or written to the register file. RISC-V is based on load-store architecture as load and store instructions tranfers between register file and the memory.

# ISA
![image](https://user-images.githubusercontent.com/82756709/172918157-45de79f7-dd01-4b97-84a6-2f25db40ed17.png)

## For immediates
![image](https://user-images.githubusercontent.com/82756709/172920702-47686768-01d6-4e82-b028-fbf133545342.png)

## Instruction Decode Table
Some instructions :p
![image](https://user-images.githubusercontent.com/82756709/172923028-91b7e08f-953d-43cf-97f9-90a743f8314f.png)


More details on 32 bit RISC-V ISA can be found [here](https://inst.eecs.berkeley.edu/~cs61c/resources/su18_lec/Lecture7.pdf)

# RISC-V CPU Diagram
![image](https://user-images.githubusercontent.com/82756709/172920290-20b4c0a4-c2fc-4b38-afae-0b401f97c8d1.png)
