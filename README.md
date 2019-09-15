# Ultima_5-Hacking
An application written in C

## Prerequisites
You may not be able to complete this assignment on a modern operating system, as there are canaries built-in to modern shells (and kernels) to prevent such a thing from occurring. I would recommend using an older Linux distribution in a virtual machine for this assignment (something prior to Linux kernel version 2.4), but you are welcome to attempt this on a modern OS and see if you can get it to work.

## Description
- This assignment focuses on buffer overflow attacks and how they can be carried out on poorly-programmed system programs.
- Review the article Smashing the Stack for Fun and Profit for a very good, detailed introduction on how to perform a stack smashing attack.
  - Link for the article: http://phrack.org/issues/49/14.html

## Assignment
- Perform a stack smash on the vuln.c code file using a C program that you create named exploit.c.
- Your program should attempt to open up a reverse shell on the attacked program as root by exploiting the buffer (you can verify this by typing the command ‘whoami‘ on the resulting terminal). The vuln.c code must be compiled in its own, separate program and must not be altered from its original state.
- Note: when running many versions of Linux, you may need to disable some address randomization.
