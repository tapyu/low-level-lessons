### Machine Code:

- **Nature**: Machine code is the lowest-level programming language that is directly executed by the computer's CPU.
- **Format**: It consists of binary code specific to the instruction set architecture (ISA) of the CPU.
- **Execution**: Machine code is executed directly by the hardware, and it is machine-dependent.
- **Example**: In x86 architecture, machine code instructions might look like binary sequences such as `10110010` `01101001` for specific operations.


### Assembly Code:

- *Nature*: Assembly code serves as a human-readable and mnemonic representation of machine code. Each assembly language instruction corresponds to a specific machine code instruction (`opcode`) that the computer's CPU can execute. Programmers write code in assembly language to have a more human-friendly way of interacting with the low-level instructions of the CPU, and then tools (*assemblers*) translate that assembly code into the actual machine code that the computer can execute. Format: It consists of symbolic representations of instructions and addresses, known as mnemonics and operands.
- *Execution*: Assembly code is not executed directly by the hardware. Instead, it needs to be translated into machine code.
- *Example*: In x86 assembly, instructions like `MOV`, `ADD`, and `JMP` are used, along with registers and memory addresses.

### Bytecode

- *Nature*: Bytecode is an intermediate representation hat is not tied to a specific machine architecture (e.g., the `.o` object file generated in the `C`/`C++` compilation process is not bytecode as it contains machine codes specific to the target architecture). For interpreted programming languages, bytecode is directly used by the interpreter to execute the program. In JIT (just-in-time) compiled programming languages, a Just-In-Time compiler translates parts of (or all) the bytecode into machine code at runtime. Then, the machine code is executed by a virtual machine or runtime environment.
- *Format*: It is in a platform-independent format, often resembling a set of instructions.
- *Execution*: Bytecode is not executed directly by the hardware. Instead, it is interpreted or translated into machine code by a virtual machine at runtime.
