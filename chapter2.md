# CTFWTF? Getting started with CTF
## Chapter 2 - Your CTF Journey and what you need

To participate in Capture the Flag (CTF) competitions, it's essential to prepare yourself with the right tools and environment. In this chapter, we'll explore the key aspects of setting up your computer and selecting the optimal operating system for competing in CTFs.

### Hardware Requirements

While CTF challenges generally do not require high-end hardware, having a computer with decent specifications is recommended for a smooth experience. A modern laptop or desktop with a reasonably fast processor, sufficient RAM (8 GB or more), and ample storage space should be adequate.

Internet Connection: A stable and reliable internet connection is crucial for accessing online resources, downloading tools, and interacting with CTF platforms during competitions. High-speed connection with low latency will ensure optimal performance.

#### A note about Mac M1 / M2 Laptops

If your hardware of choice is a modern Mac, you need to be aware of some challenges when participating in CTFs:

1. **Compatibility**: Many security tools and frameworks are traditionally developed and optimized for x86 or x86_64 architectures. While there is an increasing effort to provide ARM-compatible versions, not all tools may have full ARM support at the moment. 

2. **Virtualization and Emulation**: While popular virtualization software like VirtualBox and VMware have made progress in supporting ARM-based systems, it's essential to check for compatibility and performance issues. Additionally, some software or libraries used for emulating x86 instructions on ARM systems, like Rosetta 2 on macOS, may introduce performance overhead or limitations.

These challenges are seen the most in binary exploitation and reverse engineering categories where many challenges come along with a native x86 / x86_64 compiled binary. Unless your OS supports emulating x86 and debugging x86 binaries it may be more difficult to solve these challenges.

### Operating System (OS) Considerations

The choice of operating system depends on personal preference and the nature of the challenges you expect to encounter in the CTF. While CTFs can be approached with various operating systems, the following options are commonly used:

#### Linux
Linux distributions, such as Ubuntu or Kali Linux are popular choices among CTF participants. Linux provides a wide range of pre-installed security tools, command-line capabilities, and flexibility for customizations. It offers a rich environment for tasks like reverse engineering, binary exploitation, and scripting, making it a versatile platform for CTFs. Additionally, Linux is well-suited for the majority of challenge categories commonly encountered in CTFs.

#### Windows
Windows 10 or 11, can also be used effectively for participating in CTFs. Windows does not have as extensive a built-in toolset like Linux, it offers a user-friendly interface, compatibility with various applications, and wide-ranging software support. For challenges that involve web exploitation, forensics, or some cryptography tasks, Windows can be a viable choice. 

Windows 10 and later can also be equipped with the Windows Subsystem for Linux which gives access to a Linux system within your windows environment which makes Windows even more viable.

#### macOS
Apple's macOS can also be used for CTF competitions. It combines the usability of a user-friendly interface with the underlying power of a Unix-based system. macOS provides a comfortable development environment and offers a good balance between ease of use and the availability of security-related tools. Many CTF challenges, including cryptography, forensics, and web exploitation, can be tackled effectively on macOS.

### Tools and Software
Regardless of the operating system you choose, it's important to have a set of essential tools and software readily available. Some widely used tools for CTFs include:

* **Text Editors**: Install a versatile text editor that you're comfortable with. If you have no preference yet, try VSCode as it is fully featured, and works across all major OSs. 
* **Terminal**: Familiarize yourself with the terminal such as iTerm (macOS), Windows Terminal (from the Windows store), or the terminal emulator that comes in your favourite Linux distribution.
* **Git**: Git is a crucial tool for downloading tools you might need during a competition. Install Git and learn the basic commands.
* **Virtualization**: Tools like VirtualBox or VMware Workstation can be useful for setting up virtual machines or creating isolated environments to test and analyze vulnerable systems or malware samples.
* **Debuggers and Disassemblers**: Tools like GDB, Ghidra, or IDA Pro are valuable for reverse engineering challenges, allowing you to analyze and understand the behavior of compiled programs or binaries.

### Recommended Setup

All of that said what SHOULD you CTF with? Ultimately Linux provides the best experience when CTFing. Here's why:

* **Versatility**: Linux comes with a wide range of pre-installed security tools, scripting capabilities, and command-line flexibility. Distributions like Kali are designed with cybersecurity professionals and enthusiasts in mind, providing easy access to various tools and frameworks commonly used in CTF competitions.
* **Extensive Toolset**: Linux distributions have a vast selection of open-source security tools readily available through package managers. These tools cover a wide range of categories, including network analysis, reverse engineering, cryptography, forensics, web exploitation, and more. The Linux ecosystem provides an ideal environment for CTF challenges across diverse categories.
* **Community Support**: Linux has a large and active community of cybersecurity professionals, researchers, and enthusiasts. Linux is what most teams will be using and will have used in the past. It's most effective to be working from a level playing field with those in the community.

 Ultimately, the best OS for CTFs is the one you are most comfortable and proficient with, as it allows you to focus on honing your cybersecurity skills and solving challenges effectively. So if Linux really isn't your style, make the best of what you're most happy with.