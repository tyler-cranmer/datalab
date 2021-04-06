*****This repository was intended to document my progress as a developer and I do not authorize the use of my code in any form.***** 

This file contains materials for one instance of the attacklab.

The purpose of this assignment is to become more familiar with bit-level representations of integers (and floating point) numbers.

Files:

    ctarget

Linux binary with code-injection vulnerability.  To be used for phases
1-3 of the assignment.

    rtarget

Linux binary with return-oriented programming vulnerability.  To be
used for phases 4-5 of the assignment.

     cookie.txt

Text file containing 4-byte signature required for this lab instance.

     farm.c

Source code for gadget farm present in this instance of rtarget.  You
can compile (use flag -Og) and disassemble it to look for gadgets.

     hex2raw

Utility program to generate byte sequences.  See documentation in lab
handout.

