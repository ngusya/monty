# 0x18. C - Stacks, Queues - LIFO, FIFO

## Description

This project is a custom ByteCode interpreter, done in C.
Compilation:
```gcc -Wall -Werror -Wextra -pedantic *.c -o monty```
Usage:
```./monty byte_file.m```

The program is set to read from the file "byte_file.m" that contains one instruction per line.
It then calls the right function to modify a stack according to the instruction.
It prints custom error messages if the instruction is wrong.

