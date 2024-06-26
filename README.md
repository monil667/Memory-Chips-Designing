# Memory-Chips-Designing
**Random Access Memory:**

RAM is a type of volatile memory used for temporary data storage that requires read and write capabilities. In Verilog, RAM can be designed using behavioral or structural modeling. 
Here's an overview of the process:

*1. Specification:*
We have defined the size of the RAM as 256kb, also 
We have defined type as Static RAM Array.


*2. Module Definition:*
We Created a Verilog module specifying input and output ports, including address lines, data lines, control signals (read/write enable), and clock.

![BB](https://github.com/monil667/Memory-Project/assets/114842275/302ebc3a-47b8-46b0-9da3-487d0c69eaf8)


*3. Behavioral Modeling:*
We Used Verilog constructs like always blocks to describe the read and write operations.
We also Used a register array to model the memory storage.

So these are basic steps of designing of SRAM Array.

**Read Only Memory:**

ROM is a type of non-volatile memory used to store fixed data that does not change after programming. 
Designing ROM in Verilog involves specifying the memory content during design time.
Here's an overview of the process:

*1. Specification:*
We have defined the ROM as 1KB Dual core Read Only Memory.
We had predefined data sequence to store into ROM initially.

*2. Module Definition:*
We Created a Verilog module with input ports for address lines and output ports for data lines.

![DUAL_ROM_BB](https://github.com/monil667/Memory-Chips-Designing/assets/114842275/606ef1b4-5c7b-4f26-b195-0341bf6c3d65)

*3. Initialization:*
We Used initial blocks to read from a file using $readmemh or $readmemb to initialize the ROM content
and then Store the fixed data in a register array.

# TEST BENCH FILE:

We Created testbenches to simulate the RAM and ROM modules
and apply various test vectors to verify read/write operations for RAM and correct data retrieval for ROM.


