# x86 Assembly Cheat

x86 minimal examples. Asserts used wherever possible. Linux focus. Containers (ELF), linking, calling conventions.

1.  Featured
    1.  [Getting started](getting-started.md)
    1.  [IA-32](ia-32/)
    1.  [x86 paging tutorial](http://www.cirosantilli.com/x86-paging)
1.  Introduction
    1.  [How to learn](how-to-learn.md)
    1.  [Instruction sets](instruction-sets.md)
    1.  [Assemblers](assemblers.md)
    1.  [Pros and cons](pros-and-cons.md)
    1.  [Intel processor history](intel-processor-history.md)
    1.  [CPU Architecture](cpu-architecture.md)
        1. [CPU Optimizations](cpu-optimizations.md)
    1.  [CPU bugs](cpu-bugs.md)
    1.  [Calling conventions](calling-conventions.md)
1.  [IA-32](ia-32.md)
    1.  [main.asm](main.asm)
    1.  [Introduction](introduction.md)
        1.  [Intel vs AT&T](intel-vs-atet.md)
        1.  [Instruction encoding](https://github.com/cirosantilli/x86-instruction-encoding-tutorial)
    1.  [lib/](lib/)
    1.  [linux/](linux/)
    1.  [gas/](gas/)
    1.  [Vagrantfile](Vagrantfile)
    1.  [hello_world.asm](hello_world.asm)
    1.  Base concepts
        1.  [Registers](registers.asm)
            1. [Segment registers](segment_registers.asm)
        1.  [Addressing](addressing.asm)
        1.  [Endianess](endianess.asm)
    1.  Instructions
        1.  mov family
            1. [MOV](mov.asm)
            1. [MOVZX](movzx.asm)
            1. [MOVSX](movsx.asm)
            1. [CMOVcc](cmovcc.asm)
            1. [XCHG](xchg.asm)
            1. [LEA](lea.asm)
        1.  Flags
            1. [SETcc](setcc.asm)
        1.  Arithmetic
            1.  Addition
                1. [ADD](add.asm)
                1. [ADC](adc.asm)
                1. [INC](inc.asm)
            1.  Subtraction
                1. [SUB](sub.asm)
                1. [SBB](sbb.asm)
                1. [DEC](dec.asm)
            1.  Multiplication
                1. [MUL](mul.asm)
                1. [IMUL](imul.asm)
                1. [NEG](neg.asm)
            1.  Division
                1. [DIV](div.asm)
                1. [IDIV](idiv.asm)
            1.  [CDQ](cdq.asm)
            1.  Comparison
                1. [CMP](cmp.asm)
        1.  Bit-wise
            1.  Boolean
                1. [NOT](not.asm)
                1. [AND](and.asm)
                1. [OR](or.asm)
                1. [XOR](xor.asm)
                1. [TEST](test_instruction.asm)
            1.  Shifts
                1. [SHL, SHR](shl.asm)
                1. [SAL, SAR](sal.asm)
                1. [ROL, ROR](rol.asm)
            1.  Test
                [BT](bt.asm)
                [BTR](btr.asm)
                [BTC](btc.asm)
        1.  Branching
            1.  [Jcc](jcc.asm)
            1.  [JMP](jmp.asm)
                1. [JMP indirect](jmp_indirect.asm)
            1.  [LOOPcc](loopcc.asm)
        1.  [Stack instructions](stack-instructions.md)
            1. [enter](enter.asm)
            1. [leave](leave.asm)
            1. [pusha](pusha.asm)
            1. [pushf](pushf.asm)
        1.  [String instructions](string-instructions.md)
            1. [rep](rep.asm)
            1. [cmps](cmps.asm)
            1. [lods](lods.asm)
            1. [movs](movs.asm)
            1. [scas](scas.asm)
            1. [stos](stos.asm)
        1.  [Floating point](floating-point.md)
            1.  [FPU](fpu.asm)
            1.  [SIMD](simd.asm)
        1.  [Synchronization](synchronization.md)
            1. [XADD](xadd.asm)
            1. [CMPXCHG](cmpxchg.asm)
            1. [BTS](bts.asm)
            1. PAUSE TODO
        1.  Misc
            1. [RDRAND](rdrand.asm)
            1. [POPCNT](popcnt.asm)
            1. [RDTSC](rdtsc.asm)
            1. [NOP](nop.asm)
            1. [CPUID](cpuid.asm)
    1.  Calling conventions
        1.  [cdecl](cdecl.md)
        1.  [cdecl examples](cdecl.asm)
        1.  [stdcall](stdcall.asm)
    1.  [Encoding](encoding.asm)
    1.  [Segmentation](segmentation.md)
        1. [Rings](rings.md)
1.  [x86-64](x86-64/)
1.  [Containers](containers.md)
    1.  [ELF](elf.md)
        1. [ELF Hello World Tutorial](http://www.cirosantilli.com/elf-hello-world)
    1.  [Library](library/)
1.  [Compiler generated](compiler-generated/)
1.  [Binutils](binutils.md)
    1.  [ld](ld.md)
        1. [Linker scripts](linker-scripts/)
    1.  [readelf](readelf.md)
    1.  [objcopy](objcopy.md)
    1.  [objdump](objdump.md)
    1.  [size](size.md)
1.  [ldd](ldd.md)
1.  [intel2gas](intel2gas)
1.  [Bibliography](bibliography.md)
    1.  Related repositories
        1. [Bare metal programming](https://github.com/cirosantilli/x86-bare-metal-examples)
        1. [C++ Cheat](https://github.com/cirosantilli/cpp-cheat)
        1. [Linux Cheat](https://github.com/cirosantilli/linux-cheat)

WIP

1.  Binutils
    1. [ar](ar.md)
    1. [elfedit](elfedit.md)
    1. [nm](nm.md)
    1. [strip](strip.md)
1.  [DWARF](dwarf.md)
1.  [Symbol Versioning](symbol-versioning.md)
1.  [Debug registers](debug-registers.md)
