**OS:**
> CentOS

Compilator: NASM

Required packages: yum install gdb
		   yum update

Compilation: 	nasm -f elf64 hello64.asm -o hello64.o

Link:		ld hello64.o -o hello64

optionally, if the executable file does not appear:
ld hello64.o

Run:		./hello64

Debugging:	nasm -f dbg hello64.asm
