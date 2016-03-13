---
layout: page
title: Binary Exploitation
permalink: /binaries/
icon: info_outline
toplevel: true
---

##### Info on Binary Exploitation #####

Binary exploitation, aka Memory Corruption, has a number of facets.  These
resources are good reading for anyone seeking to understand memory corruption
exploitation.


* Basics
  * [Smashing the Stack for Fun and Profit](http://insecure.org/stf/smashstack.html)
  * [Smashing the Stack for Fun and Profit: Revived](https://avicoder.me/2016/02/01/smashsatck-revived/)
  * [Exploiting Format String Vulnerabilities](http://julianor.tripod.com/bc/formatstring-1.2.pdf)
* DEP/NX Evasion
  * [ROP](/binaries/rop.html)
* Mitigations
  * [RELRO: Not so well known memory corruption mitgation](http://tk-blog.blogspot.com/2009/02/relro-not-so-well-known-memory.html)
  * [ASLR in PaX](https://pax.grsecurity.net/docs/aslr.txt)
* [Shellcoding](/binaries/shellcoding.html)


##### Quick References #####

* x86/-64 ASM
  * [x86/x86_64 Assembly Reference](http://ref.x86asm.net/)
  * [x86 Assembly Wikibook](https://en.wikibooks.org/wiki/X86_Assembly)
  * [x86 Processor Info](http://sandpile.org/)
  * [Intel x86/x86-64 Manual](https://www-ssl.intel.com/content/dam/www/public/us/en/documents/manuals/64-ia-32-architectures-software-developer-manual-325462.pdf)
* Linux Syscalls
  * [x86 Syscall Table](http://docs.cs.up.ac.za/programming/asm/derick_tut/syscalls.html)
  * [x86-64 Syscall Table](http://blog.rchapman.org/post/36801038863/linux-system-call-table-for-x86-64)
* ABIs
  * [SysV x86-64 ABI](http://www.x86-64.org/documentation/abi.pdf)


##### Exercises for Memory Corruption #####

* Classes
  * [Modern Binary Exploitation](https://github.com/RPISEC/MBE)

