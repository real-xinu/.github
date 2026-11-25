The [`real-xinu`](https://github.com/real-xinu/) GitHub page contains software for the

```
------------------------------------------
   __    __   _____    _   _    _    _    
   \ \  / /  |__ __|  | \ | |  | |  | |   
    \ \/ /     | |    |  \| |  | |  | |   
    / /\ \    _| |_   | \   |  | |  | |   
   / /  \ \  |     |  | | \ |  \  --  /   
   --    --   -----    -   -     ----     
------------------------------------------
```

operating system and related support systems, such as servers
for the Xinu remote file system and remote disk system.  Xinu is
documented in the textbook

> **Douglas Comer, *Operating System Design -- The Xinu Approach***  
> Third Edition, CRC Press, 2025.

   We try to keep three main versions in sync: an x86 version for the Galileo
experimenter boards ([`xinu-galileo`](https://github.com/real-xinu/xinu-galileo)), an ARM version for the BeagleBone Black
experimenter boards ([`xinu-bbb`](https://github.com/real-xinu/xinu-bbb)) and an x86 version that runs on the QEMU
hypervisor ([`xinu-qemu`](https://github.com/real-xinu/xinu-qemu)).

   The easiest way to experiment with Xinu consists of starting with the QEMU
version.  Unlike the Galileo and BeagleBone Black versions, the QEMU version
does not require special hardware because it runs on any computer operating
system that supports QEMU, including Linux, Windows, and MacOS (on Apple Silicon
as well as on older Macs).  Follow the directions in the README file which will
have you install QEMU on your laptop or desktop, clone the [`xinu-qemu`](https://github.com/real-xinu/xinu-qemu) repository,
and run a setup script that will automatically create an environment for compiling
Xinu.  You can then launch Xinu in a QEMU window.

   For more information, look at the Xinu web page:

> <https://xinu.cs.purdue.edu/>

   If you have questions, you can send a message to <xinu-info@cs.purdue.edu>

<div align="right">-- Douglas Comer</div>
