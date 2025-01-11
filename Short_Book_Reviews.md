---
title: 'Short Book Reviews'
slug: 'short-book-reviews'
featured: true
description: "A collection of concise reviews of technical books I have read."
published_at: '2025-01-10'
---

Here you can find short reviews of technical books 
that I have finished. I often find myself reading 
only the chapters I need at a given time, 
so I'll be adding reviews of these books 
after exploring them enough to form an opinion.

## Recommended

**RISC-V Assembly Language Programming using ESP32-C3 and QEMU**  
*by Warren Gay*

It explains very well how to set up an environment for 32-bit 
and 64-bit RISC-V along with debugging via gdb. It provides 
all the context and fine details about standardization and 
instructions you need, so you're never left wondering, 
but it can be hard to understand everything the first time.

In this book, you write assembly in subroutines that are called 
from within C, so you're also getting taught about C calling conventions, 
which is yet another nice skill to have. 
There's also a chapter on inline assembly.

It's well rounded with chapters covering other important things, 
such as portability and determining support at runtime.

It doesn't really try to teach you thinking in assembly, examples are 
nice, but the text descriptions can be hard to follow, 
simply because you have only generic register names 
in contrast to high-level languages with named variables. 
This is not a problem if you're willing to do it by yourself, 
after a while, working with assembly gets a bit more natural.

<br>

**The RISC-V Reader: An Open Architecture Atlas**  
*by David Patterson and Andrew Waterman*

A book that calls itself an atlas, and pretty much fulfills 
that role. It's neither a trivial introduction to RISC-V, 
nor a comprehensive reference or a full story of its development, 
but it consists of bits of all these ideas.

Inside, you can find the rationale behind the design decisions, 
various insights, interesting technical details and comparisons 
with other architectures preceding RISC-V, 
such as MIPS, x86 and older ARM.

It covers most of the basic ISA (instruction set architecture) extensions, 
introduces the 64-bit base version (RV64), and describes 
the privilege modes. There is also reference material, 
such as instruction descriptions and encodings. 
They can be useful, but digital references, 
will always be more handy than a physical book in a small form factor.

All in all, it's a great book for RISC-V enthusiasts, 
if only because it's written by two of the most important RISC-V designers. 
It's quite short, but fairly priced, 
so you shouldn't be disappointed with it.

## Not Recommended

**Verilog by Example: A Concise Introduction for FPGA Design**  
*by Blaine C. Readler*

I got disappointed by this book, it provided very few examples, 
and all of them were very basic, nothing more than what you 
can find in a more practical book for beginners, 
where you can learn something more than just the syntax. 
You should check out "Getting Started with FPGAs" 
by Russell Merrick instead.

Most of the text was descriptions of examples, but nothing 
that couldn't be guessed simply by looking at the code. 
The rest of it wasn't interesting, 
and I didn't learn anything useful about digital circuit design.
