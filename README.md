4-Bit RAM
A 4-bit Random Access Memory (RAM) is a basic storage unit designed to store and retrieve 4-bit wide data. This project demonstrates the design and implementation of a simple 4-bit RAM using Verilog, providing insight into fundamental memory operations like reading and writing data.

Features
4-Bit Data Width: Each memory location stores a 4-bit value.
Configurable Address Space: Memory depth can be tailored to meet specific requirements.
Read/Write Operations: Supports both data retrieval and storage.
Synchronous Operation: Ensures data consistency with clocked operations.
Project Highlights
Inputs:

Address: Specifies the memory location to read from or write to.
Data Input: The 4-bit value to be written into memory.
Write Enable: Control signal to determine whether a write operation is performed.
Clock: Synchronizes memory operations.
Output:

Data Output: The 4-bit value read from the specified memory location.
Operation Modes:

Write Mode: Stores the input data into the addressed memory location when Write Enable is active.
Read Mode: Retrieves the data from the addressed memory location when Write Enable is inactive.
