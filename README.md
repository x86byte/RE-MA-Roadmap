# RE-MA-Roadmap
# [Reverse Engineering and Malware Analysis Roadmap](https://x86byte.github.io/x86byte_kpwn/articles/re-ma-roadmap.html)
![image](https://github.com/user-attachments/assets/6d8c7398-972b-4e81-a33e-225d4ae159b9)


Welcome to the comprehensive roadmap for mastering reverse engineering and malware analysis. This roadmap is designed to guide individuals from beginner to expert level in the field of reverse engineering and malware analysis.

## Foundations
### 0x00 Establishing a Secure Lab Environment
- [Build a Malware Analysis Lab (Self-Hosted & Cloud) - The Malware Analysis Project 101](https://youtu.be/rmSIm3BKu3Y)

### 0x01 Mastering Reverse Engineering Tools
- [Reverse Engineering For Everyone!](https://0xinfection.github.io/reversing/)
- [Reversing with Lena151  – learn OllyDbg (old, but still very useful)](https://github.com/kosmokato/Lena151)
- [REVERSING WITH IDA PRO FROM SCRATCH](http://ricardonarvaja.info/WEB/IDA%20DESDE%20CERO/EN%20INGLES/INGLES/)
- [Introduction to Windbg and debugging windows](https://www.youtube.com/playlist?list=PLhx7-txsG6t6n_E2LgDGqgvJtCHPL7UFu)
- [Writing IDA plugins in C/C++](./REbooks/IdaC%2B%2B.pdf)
  - reference : https://cpp.docs.hex-rays.com/index.html
- [IDA Plugin Writing in C++ v1.1](./REbooks/IDA%20Plugin%20Writing%20in%20C%2B%2B%20v1.1.rar)
- [IDA Plugin Writing in C++](./REbooks/IDA%20Plugin%20Writing%20in%20C%2B%2B.rar)

## Gathering Intelligence
### 0x02 Sourcing Malware Samples
- [Malware Traffic Analysis](https://www.malware-traffic-analysis.net/)
- [VX Underground](https://vx-underground.org/samples.html)
- [Malshare](http://www.malshare.com/)
- [VirusShare](https://virusshare.com/)
- [Abuse.ch](https://bazaar.abuse.ch/)
- [TheZoo](http://thezoo.morirt.com/)
- [VirusBay](https://beta.virusbay.io/)
- [MalwareBazaar](https://bazaar.abuse.ch/browse/)
- [VirusSign](https://www.virussign.com/)

### 0x03 Gathering Threat Intelligence
- [Benkow](http://benkow.cc)
- [VXVault](http://vxvault.net/)
- [Cybercrime Tracker](http://cybercrime-tracker.net/)

## Analyzing Malware Families
### 0x04 Understanding Common Malware Families
- [Malpedia](https://malpedia.caad.fkie.fraunhofer.de/)

## Practical Exercises
### 0x05 Beginner Challenges and Writeups
- first of all :
  + [Windows Stack Protection I: Assembly Code](https://www.bowneconsultingcontent.com//pub/EH/proj/cloud/ED301c_tkp/ED301c_tkp.htm) 
  + [Windows Stack Protection II: Exploit Without ASLR](https://www.bowneconsultingcontent.com//pub/EH/proj/cloud/ED302c_tkp/ED302c_tkp.htm) 
  + [Windows Stack Protection III: Limitations of ASLR](https://www.bowneconsultingcontent.com//pub/EH/proj/cloud/ED303c_tkp/ED303c_tkp.htm) 
  + [The Wild World of Windows](https://samsclass.info/127/lec/EDch6.pdf)

- [Material for Reverse Engineering Malware Practical Examples (2020 Jason Reaves)](./ObfuscationRes/RE_mpe.pdf)
- [Beginner Malware Reversing Challenges (by Malware Tech)](https://github.com/MalwareTech/Beginner-Reversing-Challenges)
- [solve the Malwarebytes CrackMe: a step-by-step tutorial](https://www.malwarebytes.com/blog/news/2017/11/how-to-solve-the-malwarebytes-crackme-a-step-by-step-tutorial)
- [MalwareTech Windows Reversing Challenge #1 Write-Ups](https://irfanalditya.github.io/posts/malwaretech-chal1/)
- [MalwareTech Windows Reversing Challenge #2 Write-Ups](https://irfanalditya.github.io/posts/malwaretech-chal2/)
- [MalwareTech Windows Reversing Challenge #3 Write-Ups](https://irfanalditya.github.io/posts/malwaretech-chal3/)
- [Crackmes.one – various crackmes to help you exercise reversing](https://crackmes.one/)
- ["Nightmare" – a reverse engineering course created around CTF tasks](https://github.com/guyinatuxedo/nightmare)
- [FlareOn Challenge writeups](https://github.com/fareedfauzi/Flare-On-Challenges)
- [Devil is Virtual: Reversing Virtual Inheritance in C++ Binaries](./ObfuscationRes/2003.05039v2.pdf)

## Understanding Low-Level Concepts
### 0x06 Assembly Language and PE Format
- [Video 1](https://www.youtube.com/watch?v=wLXIWKUWpSs&pp=ygUaIHg2IGFzc2VtYmx5IGludHJvZHVjdGlvbg%3D%3D) and [Video 2](https://www.youtube.com/watch?v=cFGJhn97e3s) for x86 assembly introduction
- Free course on assembly for other platforms
- Intel official manual on assembly language
- [An In-Depth Look Into The Win32 Portable Executable File Format](https://www.scribd.com/document/607827843/An-In-Depth-Look-into-the-Win32-Portable-Executable-File-Format)
- [An In-Depth Look into the Win32 Portable Executable File Format](https://mcsi-library.readthedocs.io/articles/2022/05/reverse-engineering-portable-executables-pe-part-2/reverse-engineering-portable-executables-pe-part-2.html)
- [Peering Inside the PE: A Tour of the Win32 Portable Executable File Format](https://coffi.readthedocs.io/en/latest/peering_inside_pe.pdf)
- [PE101](https://github.com/corkami/pics/tree/master/binary/pe101) and [PE102](https://github.com/corkami/pics/tree/master/binary/pe102) by Ange Albertini
- [Introduction to the Portable Executable (PE) File Format](https://bytepointer.com/resources/pietrek_pe.htm)
- [Win32 Portable Executable File Format](https://www.fireeye.com/content/dam/fireeye-www/services/pdfs/sans-for610-pe.pdf)
- [Inside Windows PE](https://www.microsoftpressstore.com/articles/article.aspx?p=2201309)
- [Windows Internals 7th Edition](https://www.microsoftpressstore.com/store/windows-internals-part-1-system-architecture-processes-9780135462409)
- [Dynamic Linking and Windows PE](https://docs.microsoft.com/en-us/windows/win32/dlls/dynamic-linking)
- [Understanding Windows PE Files](https://0xrick.github.io/win-internals/pe1/)
- [Binary Analysis Cookbooks](https://binary.ninja/cookbook/)
- [Windows PE Parsing with Python](https://www.contextis.com/en/blog/malware-analysis-windows-pe-file-parsing-python)
- [Automation Techniques in C++ Reverse Engineering](./ObfuscationRes/CPP-Dynamic-Type-Recovery.pdf)

### Additional Assembly Resources
- [Modern x64 Assembly](https://www.youtube.com/playlist?list=PLKK11Ligqitg9MOX3-0tFT1Rmh3uJp7kA)
- [Intro to x86 Assembly Language](https://www.youtube.com/playlist?list=PLmxT2pVYo5LB5EzTPZGfFN0c2GDiSXgQe)
- [x86_64 Linux Assembly](https://www.youtube.com/playlist?list=PLetF-YjXm-sCH6FrTz4AQhfH6INDQvQSn)
- [Intro x86 (32 bit)](https://www.youtube.com/playlist?list=PL038BE01D3BAEFDB0)
- [Practical x64 Assembly and C++ Tutorials](https://www.youtube.com/playlist?list=PL0C5C980A28FEE68D)
- [Introductory Intel x86: Architecture, Assembly, Applications, & Alliteration](http://opensecuritytraining.info/IntroX86.html)
- [LINUX SYSTEM CALL TABLE FOR X86 64](https://blog.rchapman.org/posts/Linux_System_Call_Table_for_x86_64/)
- [Learning assembly for linux-x64](https://github.com/0xAX/asm)
- [x86-assembly-cheat](https://github.com/cirosantilli/x86-assembly-cheat)
- [x86 Assembly Guide](https://www.cs.virginia.edu/~evans/cs216/guides/x86.html)
- [Assembly’s Perspective](https://blog.stephenmarz.com/2020/05/20/assemblys-perspective/)
- [A Crash Course in x86 Assembly for Reverse Engineers](https://sensepost.com/blogstatic/2014/01/SensePost_crash_course_in_x86_assembly-.pdf)
- [Understanding C by learning assembly](https://www.recurse.com/blog/7-understanding-c-by-learning-assembly)
- [x86 Assembly Crash Course → YouTube](https://www.youtube.com/watch?v=75gBFiFtAb8)
- [x86 and amd64 instruction reference](https://www.felixcloutier.com/x86/index.html)
- [Learn x86_64 Assembly](https://gpfault.net/posts/asm-tut-0.txt.html)
  - [Part 1](https://gpfault.net/posts/asm-tut-1.txt.html)
  - [Part 2](https://gpfault.net/posts/asm-tut-2.txt.html)
- [x86-64 Assembly Programming with Ubuntu](http://www.egr.unlv.edu/~ed/assembly64.pdf)
- [Assembly for beginners](https://pacman128.github.io/pcasm/)
- [Assembly Language Succinctly](https://www.syncfusion.com/ebooks/assemblylanguage)
- [Everything you want to know about x86 microcode, but might have been afraid to ask](https://media.ccc.de/v/34c3-9058-everything_you_want_to_know_about_x86_microcode_but_might_have_been_afraid_to_ask)
- [Beginner Write your first Assembly Language program – Hello World!! [explained]](http://cssimplified.com/computer-organisation-and-assembly-language-programming/beginner-write-your-first-assembly-language-program-hello-world-explained)
- [Quick Guide to Assembly in 161 - Berkeley](https://inst.eecs.berkeley.edu/~cs161/sp15/discussions/dis06-assembly.pdf)
- [godbolt.org - Code ↔️ Assembly](https://godbolt.org/)
- [Introduction to ARM](http://opensecuritytraining.info/IntroARM.html)
- [INTRODUCTION TO ARM ASSEMBLY BASICS](https://azeria-labs.com/writing-arm-assembly-part-1/)
- [Art of Assembly Language, The - Hyde, Randall](./REbooks/Art%20of%20Assembly%20Language%2C%20The%20-%20Hyde%2C%20Randall.pdf)
- [Assembly Language Step-by-Step: Programming with Linux - Duntemann, Jeff](./REbooks/Assembly%20Language%20Step-by-Step_%20Programming%20with%20Linux%20-%20Duntemann%2C%20Jeff.pdf)

### 0x07 Programming for Reverse Engineering
- C/C++, Python, and Assembly
- [MalwareTech's article on programming for malware analysis](https://www.malwaretech.com/2018/03/best-programming-languages-to-learn-for-malware-analysis.html)
- Recommended learning resources:
  - x86 Assembly: [Iczelion's tutorial](https://github.com/VishalRashmika/Iczelions-Assembly-Tutorials/blob/main/README.md), [Win32 Assembler for Crackers by Goppit](https://www.scribd.com/document/659839309/Win32-Assembler-Coding-for-Crackers-PL-Kody-zrodlowe)
  - C/C++: [The C Programming language - by Kernighan & Ritchie](https://www.amazon.com/Programming-Language-2nd-Brian-Kernighan/dp/0131103628), [The C++ Programming language](https://www.amazon.com/C-Programming-Language-4th/dp/0321563840), [Linux Programming by example - by Kurt Wall](https://www.amazon.com/Linux-System-Programming-Embedded-Developers/dp/1593272200)
- [Windows System Programming](https://www.amazon.com/Windows-System-Programming-4th-Addison-Wesley/dp/0321657748) book
- [CPP / C++ Notes - Windows API Programming Win32](https://web.archive.org/web/20220407010232mp_/https://caiorss.github.io/C-Cpp-Notes/WindowsAPI-cpp.html)

### Start Now with These Books!
After all this learning, you can now start with these essential books on **Reverse Engineering & Exploitation**:

#### Reverse Engineering & Exploitation
- [Reversing: Secrets of Reverse Engineering - Eilam, Eldad](./REbooks/Reversing_%20Secrets%20of%20Reverse%20Engineering%20-%20Eilam%2C%20Eldad.pdf)
- [Practical Reverse Engineering: x86, x64, ARM, Windows Kernel - Dang, Bruce & Gazet, Alexandre & Bachaalany, Elias](./REbooks/Practical%20Reverse%20Engineering_%20x86%2C%20x64%2C%20ARM%2C%20Windows%20Kernel%2C%20Rev%20Obfuscation%20-%20Dang%2C%20Bruce%20%26%20Gazet%2C%20Alexandre%20%26%20Bacha%E2%80%A6.pdf)


## Malware Unpacking
### 0x08 Manual Unpacking Techniques
- some ways...
  - way one : https://medium.com/@dbragetti/unpacking-malware-685de7093e5
  - way two : https://www.travismathison.com/posts/Manually-unpacking-malware/
- [manual unpacking](https://www.youtube.com/playlist?list=PLt9cUwGw6CYGfoSL9PUlpKi23z0_R2gz-)
- [Malware Analysis - ConfuserEx 2 Deobfuscation with Python and dnlib, BBTok Loader](https://www.youtube.com/watch?v=Pjy50g6naMU)
- [Unpacking UPX packer](https://0xh3xa.github.io/defensive/unpack-upx/)
- [How to unpack UPX packed malware with a SINGLE breakpoint](https://infosecwriteups.com/how-to-unpack-upx-packed-malware-with-a-single-breakpoint-4d3a23e21332)
- [LLVM-powered deobfuscation of virtualized binaries](https://blog.thalium.re/posts/llvm-powered-devirtualization/)
- [Automating Malware Deobfuscation with Binary Ninja - Writing a Static Unpacker](https://cfp.recon.cx/media/recon2024/submissions/DDHBFN/resources/Slides_-_Automating_Malware_Deobfuscation_with_Bi_2dAAJCN.pdf)
- [How To Quickly Unpack Qbot Loader Malware](https://youtu.be/9EkRW6rh6DI)
- [Anti-UPX Unpacking Technique - explains the details of Anti-UPX Unpacking technique, which is often applied to Linux-targeting malware](https://blogs.jpcert.or.jp/en/2022/03/anti_upx_unpack.html)
- [x64Unpack: Hybrid Emulation Unpacker for 64-bit Windows Environments and Detailed Analysis Results on VMProtect 3.4](https://ieeexplore.ieee.org/abstract/document/9139515)
- [The Art Of Unpacking part 1](./ObfuscationRes/The%20Art%20of%20Unpacking%20-%20Part1.pdf)
- [The Art Of Unpacking part 2](./ObfuscationRes/The%20Art%20of%20Unpacking%20-%20Part2.pdf)
- [Statically Unpacking Shellcode-based PE Loaders](./ObfuscationRes/Statically%20Unpacking%20Shellcode-based%20PE%20Loaders.pdf)
- [DOSfuscation: Exploring the Depths of Cmd.exe Obfuscation and Detection Techniques](./ObfuscationRes/invoke_dosfuscation_techniques_for_fin_style_dos_level_cmd_obfuscation.pdf)

  
## Advanced Techniques
### 0x09 Virtualization-based Protectors
- [Workshop: VM-based Obfuscation Analysis](https://synthesis.to/2021/10/21/vm_based_obfuscation.html)
- [Tigress: Virtualization-Based Software Obfuscation Pt. 1](https://www.mitchellzakocs.com/blog/tigress)
- [VMProtect 3: Virtualization-Based Software Obfuscation Pt. 2](https://www.mitchellzakocs.com/blog/vmprotect3)
- [Discussion on reverse engineering virtualization](https://www.youtube.com/watch?v=PAG3M7mWT2c&t=13229s)
- [VMProtect 2 – Detailed Analysis of the Virtual Machine Architecture](https://www.tetraph.com/security/vulnerability-scanning/vmprotect-2-detailed-analysis-virtual-machine-architecture/)
- [VMProtect 2 – Part Two, Complete Static Analysis](https://www.tetraph.com/security/vulnerability-scanning/vmprotect-2-part-two-complete-static-analysis/)
- [SpeakEasy: a writeup solving a challenge from UIUCTF 2021](https://medium.com/@acheron2302/speakeasy-writeup-3af3375ab63)
- [Tickling VMProtect with LLVM](https://www.synthesis.to/2021/10/21/vm_based_obfuscation.html)
- [Cracking programs with custom virtualization-based protectors](https://www.malwaretech.com/challenges/windows-reversing/vm1)
- [Dealing with Virtualization packer](./ObfuscationRes/boris_lau_virtualization_obfs.pdf)
- [Unpacking Virtualization Obfuscators](./ObfuscationRes/Unpacking%20Virtualization%20Obfuscators.pdf)
- [Virtual Machine RE-building](./ObfuscationRes/Virtual%20Machine%20RE-building.pdf)
- [Breaking State-of-the-Art Binary Code Obfuscation via Program Synthesis](./ObfuscationRes/The-Art-Binary-Code-Obfuscation-Via-Program-Synthesis.pdf)
- [Advanced Binary Deobfuscation](./ObfuscationRes/Advanced-Binary-Deobfuscation.pdf)
- [Deobfuscation of Lumma Stealer](https://ryan-weil.github.io/posts/LUMMA-STEALER)
- [Analyzing Mutation-Coded - VM Protect and Alcatraz English](https://hackyboiz.github.io/2025/09/11/banda/LLVM_based_VMP/en/)
- [ESET’S GUIDE TO DEOBFUSCATING AND DEVIRTUALIZING FINFISHER](./ObfuscationRes/WP-FinFisher.pdf)

### 0x0a Malware Injection and Hooking
- [A walk-through various techniques (by Endgame)](https://www.endgame.com/blog/technical-blog/ten-process-injection-techniques-technical-survey-common-and-trending-process)
- [Ready-made demos of various code injection techniques (source code)](https://github.com/odzhan/injection)
- [Review of various injection techniques (BlackHat 2019) Video - PDF](https://www.blackhat.com/us-19/briefings/schedule/index.html#practical-approach-to-process-injection-14279)
- [Author's PE injection demos (source code)](https://github.com/hasherezade/demos)
- ["Inline Hooking for programmers" (by MalwareTech) - Part 1 and Part 2](https://malwaretech.com/how-to-write-a-rootkit)
- [Windows API Hooking (article in Red Teaming Experiments)](https://redteaming.io/)
- [Simple userland rootkit - a case study](https://blog.malwarebytes.com/threat-analysis/2016/12/simple-userland-rootkit-a-case-study/)

### 0x0b Kernel-mode Malware

Before we dive into kernel-mode malware and rootkit techniques, it's important to understand the fundamentals of driver development and kernel programming. Below are some great starting points that will guide you through these concepts and provide a solid foundation.

#### Basic Driver Development Resources
- [Catalog of key Windows kernel data structures](https://web.archive.org/web/20211106153221mp_/https://codemachine.com/articles/kernel_structures.html)
1. **Driver Development Part 1: Introduction to Drivers**  
   [CodeProject: Introduction to Drivers](https://www.codeproject.com/articles/9504/driver-development-part-1-introduction-to-drivers)

2. **Driver Development Part 2: Introduction to Implementing IOCTLs**  
   [CodeProject: Introduction to Implementing IOCTLs](https://www.codeproject.com/articles/9575/driver-development-part-2-introduction-to-implemen)

3. **Driver Development Part 3: Introduction to Driver Contexts**  
   [CodeProject: Introduction to Driver Contexts](https://www.codeproject.com/articles/9636/driver-development-part-3-introduction-to-driver-c)

4. **Driver Development Part 5: Introduction to the Transport Device Interface**  
   [CodeProject: Introduction to Transport Device Interface](https://www.codeproject.com/articles/9974/driver-development-part-5-introduction-to-the-tran)

5. **Driver Development Part 6: Introduction to Display Drivers**  
   [CodeProject: Introduction to Display Drivers](https://www.codeproject.com/articles/12878/driver-development-part-6-introduction-to-display)

#### Additional Resources

- **Memory Management in Kernel Mode**  
  The best starting point for these aspects is tutorials written by Four-F:  
  - [How The Kernel Manages Your Memory](https://manybutfinite.com/post/how-the-kernel-manages-your-memory/)
  - [Driver Basics - DMA Concepts](https://www.osronline.com/article.cfm%5Earticle=539.htm)
  - [X-DMA - Extreme DMA for Performance](https://www.osronline.com/article.cfm%5Earticle=19.htm)
  - [MmMapLockedPages(SpecifyCache) with AccessMode == UserMode](https://www.osronline.com/article.cfm%5earticle=26.htm)
  - [A Common Topic Explained - Sharing Memory Between Drivers and Applications](https://www.osronline.com/article.cfm%5earticle=39.htm)
  - [Windows NT Virtual Memory (Part I)](https://www.osronline.com/article.cfm%5earticle=71.htm)
  - [Windows NT Virtual Memory (Part II)](https://www.osronline.com/article.cfm%5earticle=60.htm)
  - [Finding File Contents in Memory](https://www.osronline.com/article.cfm%5earticle=280.htm)
 
- **Handling IRPs (I/O Request Packets)**
  - [Properly Pending IRPs - IRP Handling for the Rest of Us](https://www.osronline.com/article.cfm%5earticle=21.htm)
  - [Proper Completion -- Resubmitting IRPs from within a Completion Routine](https://www.osronline.com/article.cfm%5earticle=391.htm)
  - [Rules for Irp Dispatching and Completion Routines](https://www.osronline.com/article.cfm%5earticle=214.htm)
  - [Beyond IRPs: Driver to Driver Communications](https://www.osronline.com/article.cfm%5earticle=177.htm)
  - [IrpTracker](https://www.osronline.com/article.cfm%5earticle=199.htm)
  - [Rolling Your Own - Building IRPs to Perform I/O](https://www.osronline.com/article.cfm%5Earticle=87.htm)
  - [The Truth About Cancel - IRP Cancel Operations (Part I)](https://www.osronline.com/article.cfm%5Earticle=78.htm)
  - [The Truth About Cancel - IRP Cancel Operations (Part II)](https://www.osronline.com/article.cfm%5earticle=72.htm)
    
  ~ A must-read for driver writers:  
    - [Microsoft: Handling IRPs](https://learn.microsoft.com/en-us/windows-hardware/drivers/kernel/handling-irps)
  
- **The Basics:Bugchecks Explained**
  + [https://www.osronline.com/article.cfm%5earticle=334.htm](PFN_LIST_CORRUPT)
  + [https://www.osronline.com/article.cfm%5Earticle=335.htm](PAGE_FAULT_IN_NONPAGED_AREA)
  + [https://www.osronline.com/article.cfm%5earticle=336.htm](KERNEL_DATA_INPAGE_ERROR)
  + [https://www.osronline.com/article.cfm%5Earticle=337.htm](NO_MORE_IRP_STACK_LOCATIONS)
    
#### Important Books for Kernel and Driver Development

  - [Windows Kernel Programming (First Edition)](REbooks/Windows_Kernel_Programming_Pavel_Yosifovich.pdf) *(Available in the REbooks folder)*
  - [Windows Kernel Programming, 2nd Edition](REbooks/Windows_Kernel_Programming_2nd_Edition_Pavel_Yosifovich.pdf) *(Available in the REbooks folder)*
  - [Windows NT Device Driver Development](REbooks/Windows_NT_Device_Driver_Development.pdf) *(Available in the REbooks folder)*
  - [Windows Internals, Part 1, 7th Edition - 2017](https://dn790000.ca.archive.org/0/items/windows-internals-part1-7th/windows-internals-part1-7th.pdf)
  - [Windows Internals, 7th Edition, Part 2 - 2021](REbooks/WinInternals_p2.zip) *(Available in the REbooks folder just extrat the zip)*


#### Web Resources

- **OSR Online**: The first and most important resource about Windows Driver Development  
  [OSR Online](http://www.osronline.com/)

- **Other Useful Blogs and Resources**  
  - [J00ru Blog - Reverse Engineering & Kernel Research](http://j00ru.vexillium.org/)  
  - [Rootkit Analysis Tutorial PDF](https://www.sekoia.fr/blog/wp-content/uploads/2016/10/Rootkit-analysis-Use-case-on-HIDEDRV-v1.6.pdf) *(available in the current repo under the REbooks folder)*

#### Transition to Kernel-mode Malware

Once you’ve gone through these foundational resources, you’ll have a better understanding of driver development, IRPs, memory management, and more. Now we can proceed to advanced topics like kernel-mode malware, rootkit analysis, and related techniques.

---

#### Key Resources for Kernel-mode Malware and Rootkit Techniques

- [Starting with Windows Kernel Exploitation - setting up the lab](https://hshrzd.wordpress.com/2017/05/28/starting-with-windows-kernel-exploitation-part-1-setting-up-the-lab/)
- [Brief introduction to driver analysis methods by Matt Hand](https://hshrzd.wordpress.com/2017/05/28/starting-with-windows-kernel-exploitation-part-1-setting-up-the-lab/)
- [Rootkit analysis tutorial](http://www.sekoia.fr/blog/wp-content/uploads/2016/10/Rootkit-analysis-Use-case-on-HIDEDRV-v1.6.pdf)

#### Kernel-mode Rootkit Techniques:

- [Hooking IDT](https://resources.infosecinstitute.com/hooking-idt/)
- [SSDT hooks](https://www.adlice.com/kernelmode-rootkits-part-1-ssdt-hooks/)
- [IRP hooks](https://www.adlice.com/kernelmode-rootkits-part-2-irp-hooks/)
- [Kernel filters](https://www.adlice.com/kernelmode-rootkits-part-3-kernel-filters/)



### 0x0c Going Deeper
- [Malware infecting MBR, bootkits, and UEFI firmware](https://securelist.com/bootkits-the-ultimate-in-persistent-malware/58221/)
- [UEFI Reverse Engineering, Vulnerability Discovery, and Exploit Development](https://www.leviathansecurity.com/blog/uefi-is-the-new-bios)
  
## Learning Resources
### 0x0d Courses and Tutorials
- [Mytechnotalent's Reverse Engineering Repository](https://github.com/mytechnotalent/Reverse-Engineering)
- [Octopus Labs](http://legend.octopuslabs.io/sample-page.html)
- [Open Security Training](http://opensecuritytraining.info/Training.html)
- [Practical Malware Analysis learning materials](https://samsclass.info/126/126_S17.shtml)
- [Malware Analysis course (University of Cincinnati)](https://www.uc.edu/ce/cyber/courses/malware-analysis.html)
- [Red/purple teaming: a malware development course by 0xPat](https://twitter.com/0xPat)
- [Building C2 implants in C++](https://malwareunicorn.org/workshops.html)
- [Hasherezade's malware training repository](https://github.com/hasherezade/malware_training_vol1)

  ### - Obfuscation
    - [Practical Obfuscating Programs](./ObfuscationRes/Practical%20Obfuscating%20Programs.PDF)
    - [Program Obfuscation](./ObfuscationRes/Program%20Obfuscation.PDF)
    - [Invoke-Obfuscation: PowerShell obFUsk8tion Techniques & How To (Try To) D""e`Tec`T 'Th'+'em'](./ObfuscationRes/invoke-obfuscation-nullcon.pdf)
    - [Obfuscation-based Malware Update: A comparison of Manual and Automated Methods](./ObfuscationRes/bebc0c4c5dcfb3ffd41ac701adafe88d85ce.pdf)
    - [Techniques of Program Code Obfuscation for Secure Software](./ObfuscationRes/Techniques_of_Program_Code_Obfuscation_for_Secure_.pdf)
    - [A Tutorial on Software Obfuscation](./ObfuscationRes/Orca.pdf)
    - [CODE OBFUSCATION AND VIRUS DETECTION](./ObfuscationRes/Code%20obfuscation%20and%20virus%20detection.pdf)
    - [Software Obfuscation with Non-Linear Mixed Boolean-Arithmetic Expressions](./ObfuscationRes/ObfMBA.pdf)
    - [ COMBATING CONTROL FLOW FLATTENING IN .NET MALWARE](./ObfuscationRes/VB2022-Combating-control-flow-flattening-in-NET-malware.pdf)
    - [Modern obfuscation techniques (Roman Oravec 2021)](./ObfuscationRes/ModernObfuscationTechniques.pdf)
    - [Breaking Mixed Boolean-Arithmetic Obfuscation in Real-World Applications by the goat Tim Blazytko](./ObfuscationRes/recon25_mba_obfuscation.pdf)
    - [Seeing through obfuscation: interactive detection and removal of opaque predicates](./ObfuscationRes/thesis.pdf)
    - [Technical Challenges of Indirect Control Flow](https://codedefender.io/blog/2024/07/02/)
    - [MODERN MALWARE: OBFUSCATION AND EMULATION DEF CON CHINA 1.0 (2019)](./ObfuscationRes/DEFCON_CHINA_ALEXANDRE.pdf)

### 0x0e YouTube Channels and Videos
- [Malware Analysis For Hedgehogs](https://www.youtube.com/channel/UCVFXrUwuWZ3Uk6ZuIzP5RvQ)
- [OALabs](https://www.youtube.com/c/OALabs/videos)
- [Colin's channel about malware](https://www.youtube.com/channel/UCQN2DsjnYH60SFBIA6IkNwg)
- [DuMp-GuY TrIcKsTeR](https://www.youtube.com/user/hexacorn)

### 0x0f Recommended Books
- [Practical Malware Analysis: A Hands-On Guide to Dissecting Malicious Software](./REbooks/Practical%20Malware%20Analysis_%20The%20Hands-On%20Guide%20to%20Dissecting%20Malicious%20Software%20-%20Sikorski%2C%20Michael%20%26%20Honig%2C%20Andrew.pdf)
- [The Art of Computer Virus Research and Defense – Peter Szor](https://www.amazon.com/Art-Computer-Virus-Research-Defense/dp/0321304543)
- ["The "Ultimate"Anti-Debugging Reference" – by Peter Ferrie](https://www.amazon.com/Ultimate-Anti-Debugging-Reference-Peter-Ferrie/dp/1500494501)
- [Malware Analyst's Cookbook and DVD: Tools and Techniques for Fighting Malicious Code](https://www.amazon.com/Malware-Analysts-Cookbook-DVD-Techniques/dp/0470613033)
- [Hacker Disassembling Uncovered – by Kris Kaspersky](https://www.amazon.com/Hacker-Disassembling-Uncovered-Kaspersky/dp/193176946X)
- [The Rootkit Arsenal: Escape and Evasion in the Dark Corners of the System](https://www.amazon.com/Rootkit-Arsenal-Escape-Evasion-Corners/dp/144962636X)
- [Rootkits and Bootkits – by Alex Matrosov, Eugene Rodionov, and Sergey Bratus](https://www.amazon.com/Rootkits-Bootkits-Alex-Matrosov/dp/1593277164)
- [Windows System Programming (4th edition) – by Johnson M. Hart](https://www.amazon.com/Windows-System-Programming-4th-Addison-Wesley/dp/0321657748)

## Tips and Advice
### 0x10 Staying Motivated and Advancing Your Career
- Stay curious and eager to learn
- Practice, practice, practice
- Engage with the community
- Contribute and share your knowledge
- Stay up-to-date with the latest trends and techniques
- Develop strong programming skills in languages like C/C++, Python, and Assembly
- Embrace failure as a learning opportunity
- Maintain a safe and controlled environment for your analysis
- Respect intellectual property and adhere to ethical guidelines

### 0x11 Getting a Malware Analyst Job
- Contribute to the community through research, blog posts, or open source projects
- Stay active and engaged in the field by attending conferences and participating in CTFs
- Build a solid online presence by sharing your work and insights on platforms like GitHub and Twitter
- Network with industry professionals and join relevant communities and forums
- Continuously update your skills and knowledge through self-study and formal training programs

## Conclusion
This comprehensive roadmap provides a step-by-step guide for mastering reverse engineering and malware analysis. By following the suggested resources and engaging in practical exercises, you can build a strong foundation, develop advanced skills, and position yourself for a successful career in this field. Remember to stay motivated, curious, and always eager to learn. Good luck on your reverse engineering and malware analysis journey!

## Additional Resources
### Blogs and Websites
- [MalwareTech](https://www.malwaretech.com/)
- [Hasherezade's Blog](https://hshrzd.wordpress.com/)
- [Malwarebytes Labs](https://blog.malwarebytes.com/)
- [FireEye Threat Research Blog](https://www.fireeye.com/blog/threat-research.html)
- [Talos Intelligence Blog](https://blog.talosintelligence.com/)
- [Securelist by Kaspersky](https://securelist.com/)
- [The Malware Analyst's Cookbook](https://www.malwarecookbook.com/)
- [0xec](https://0xec.blogspot.com/)
- [Malwarebytes Unpacked](https://blog.malwarebytes.com/category/unpacked/)
- [SANS Internet Storm Center](https://isc.sans.edu/)
- [MalwareMustDie](http://malwaremustdie.blogspot.com/)
- [ReversingLabs](https://www.reversinglabs.com/blog)

### Forums and Communities
- [MalwareTips](https://malwaretips.com/)
- [Reverse Engineering Stack Exchange](https://reverseengineering.stackexchange.com/)
- [KernelMode.info](https://www.kernelmode.info/forum/)
- [Wilders Security Forums](https://www.wilderssecurity.com/)
- [Malware Analysis Forums on Reddit](https://www.reddit.com/r/Malware/)
- [VirusTotal Community](https://www.virustotal.com/gui/community)
- [OSR Developer Community](https://community.osr.com)
- [UnKnoWnCheaTs](https://www.unknowncheats.me/forum/index.php)
- [Reverse Engineering - Stack exchange](https://reverseengineering.stackexchange.com/)
- [ru-board](http://forum.ru-board.com)
- [R0](https://forum.reverse4you.org/categories)
- [CrackLab](https://cracklab.team/index.php)

### Tools and Software
- [IDA Pro](https://www.hex-rays.com/products/ida/)
- [Ghidra](https://ghidra-sre.org/)
- [x64dbg](https://x64dbg.com/)
- [OllyDbg](http://www.ollydbg.de/)
- [Immunity Debugger](https://www.immunityinc.com/products/debugger/)
- [Wireshark](https://www.wireshark.org/)
- [Cuckoo Sandbox](https://cuckoosandbox.org/)
- [PEStudio](https://www.winitor.com/)
- [Volatility](https://www.volatilityfoundation.org/)
- [Sysinternals Suite](https://docs.microsoft.com/en-us/sysinternals/)
- [YARA](https://virustotal.github.io/yara/)
- [Capstone](https://www.capstone-engine.org/)
- [Radare2](https://www.radare.org/)
- [Binary Ninja](https://binary.ninja/)

### Online Platforms and Challenges
- [MalwareBazaar](https://bazaar.abuse.ch/)
- [VirusTotal](https://www.virustotal.com/gui/home)
- [Hybrid Analysis](https://www.hybrid-analysis.com/)
- [Flare-On Challenge](https://www.fireeye.com/blog/threat-research/2019/08/announcing-the-sixth-annual-flare-on-challenge.html)
- [CTFTime](https://ctftime.org/)
- [Hack The Box](https://www.hackthebox.eu/)




## Upcoming Resources

I will be adding some random books to the **REbooks** folder soon. Stay tuned for more resources!



## Acknowledgments
A big thank you to all the researchers, authors, and contributors who have shared their knowledge and resources in the field of reverse engineering and malware analysis. This roadmap wouldn't have been possible without their valuable contributions.

## Contributing
Contributions are welcome! If you have any suggestions, resources, or improvements to this roadmap, please feel free to open an issue or submit a pull request.


## channel 
## Join OrcaCyberWeapons on Telegram!

Are you ready to dive into the depths of cybersecurity, reverse engineering, and advanced threat analysis? Look no further than OrcaCyberWeapons, your gateway to the world of cutting-edge security research and exploration.

**What We Offer:**
- **Advanced Cybersecurity Insights:** Delve into the latest trends, techniques, and strategies employed by cyber adversaries, shedding light on the vast world of malware, exploits, APTs, and cybercrime across all platforms.
- **Reverse Engineering Expertise:** Uncover the inner workings of sophisticated malware, dissect exploit techniques, and explore the art of reverse engineering with our community of seasoned professionals and enthusiasts.
- **Malware Development and Analysis:** Gain valuable insights into the creation, analysis, and mitigation of malware, understanding its behavior, impact, and countermeasures.
- **APT Techniques and Defense Strategies:** Explore the realm of advanced persistent threats (APTs), dissect their tactics, and fortify your defenses against sophisticated cyber adversaries.

Whether you're a seasoned cybersecurity professional, an aspiring ethical hacker, or a curious enthusiast, OrcaCyberWeapons provides a platform for in-depth discussions, practical insights, and collaborative exploration of the ever-evolving cybersecurity landscape.

Join us on Telegram and embark on a journey of discovery, knowledge sharing, and continuous learning in the realm of cybersecurity and beyond.

[Join OrcaCyberWeapons on Telegram](https://t.me/OrcaCyberWeapons)
