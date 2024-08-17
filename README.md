# LSCD11
## The full Lewis Sanders Computing Device 11 (LSCD11) repository, containing designs, assemblers, and emulators.

The **LSCD11** computer is an 8-bit homebrew computer architecture. The **LSCD11** is also the first LSCD computer. Design on this computer began in fall of 2023, and was completed and solidified near the first half of 2024. The LSCD11 has two registers: the accumulator, and the return register. It has a unusual 11 bit RAM and program memory address width (over 2KB of data.) Additionally, instructions are split into two parts: the opcode (there are 16 opcodes) and the operand(memory adress, immediate value), with 1 or 4 unused bits in an instruction.

However, due to the fact that the design for the LSCD11 is not turing complete, there is no emulator provided, and only a janky assembler and a spec file.=
