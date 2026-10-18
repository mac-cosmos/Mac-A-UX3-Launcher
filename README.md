[README.md](https://github.com/user-attachments/files/33617737/README.md)


<strong>Mac A-UX3 Launcher</strong>

<i>A native macOS launcher for running Apple's A/UX UNIX operating system with the Shoebill 
Macintosh II emulator on Apple Silicon (ARM64).</i>

<strong>Version: 1.0</strong><br>
<strong>Project:</strong> Mac A-UX3 Launcher<br>
<strong>Developer:</strong> Thomas Hemenway<br>
<strong>Website:</strong> www.mac-cosmos.com

1. <strong>Project Overview:</strong>
Mac A-UX3 Launcher is a custom macOS application based on Peter Rutenbar's original 
Shoebill emulator project. Its purpose is to help preserve access to Apple's legacy A/UX 
operating system through a convenient launcher interface on modern Mac hardware.
The project maintains two separate application editions:

	<strong>•	Apple Silicon edition (ARM64) - for Apple Silicon Macs.<br>
	•	Intel edition (x86_64) - for Intel-based Macs.</strong>
	
<i>Both editions have been built and tested on physical Mac hardware across multiple macOS 
releases. The two editions are maintained separately rather than as a Universal Binary.</i>

2. <strong>Apple Silicon Edition</strong> — Test matrix test hardware: Apple M4 Mac<br>
Operating system • macOS 15 Sequoia • PASS<br>
Operating system • macOS 26 Tahoe • PASS<br>
Operating system • macOS 27 Golden Gate • PASS<br>

Application architecture: Apple Silicon (ARM64)

2. <strong>Intel Edition</strong> - Test matrix test hardware: Intel Mac tower with multiple operating systems installed across drives 
and partitions, including configurations using OpenCore Legacy Patcher (OCLP).<br>
Operating system • macOS 12 Monterey • PASS<br>
Operating system • macOS 13 Ventura • PASS<br>
Operating system • macOS 14 Sonoma • PASS<br>
Operating system • macOS 15 Sequoia • PASS<br>

<i>Application designed to work on macOS 12 Monterey to macOS 27 Golden Gate. Support for 
Intel app ended with macOS 27. Application architecture: Intel x86_64
The Intel edition was confirmed to identify itself as an Intel app in macOS Get Info.</i>

Application architecture: Intel (x86_64)

3. <strong>Functional Verification</strong><br>
<i>The following results were reported during testing:</i><br>
• Application  auto launches successfully.<br>
• The pre-configured paths to user supplied files all work pointing to Resources.<br>
• The emulator operates correctly in every tested operating system.<br>
• The application window opens centered on the screen.<br>
• Window positioning behaves as intended.<br>
• The launcher interface and implemented features work as expected.<br>
• The Intel edition operates successfully on Intel hardware.<br>
• The Apple Silicon edition operates successfully on Apple Silicon hardware.

4. <strong>Build and Preservation Notes</strong><br>
The Intel edition was built successfully from the project source using Xcode, 
targeting x86_64 with a minimum macOS deployment target of 12.0.
The resulting Intel application was tested successfully on macOS 12 Monterey, macOS 13 
Ventura, macOS 14 Sonoma, and macOS 15 Sequoia.

<strong>Important:</strong> <i>The build's deployment target is macOS 12.0. Successful operation on older macOS 
versions has been established by running the old Shoebill version which runs on Mac 10.8 or higher. 
The Apple Silicon and Intel editions are maintained as separate builds rather than a Universal Binary. 
The project is intended to preserve legacy operating systems and applications through custom 
virtual-machine and emulation environments. Original copyright notices and the project's 
BSD 2-Clause license are fully retained.</i> 

<strong>Mac A-UX3 Launcher Version 1.0</strong><br>
<i>(c)2025-2026 Thomas Hemenway Apple Developer 2004-Present</i><br> 
https://www.mac-cosmos.com

Many thanks to Peter Rutenbar for creating the original Shoebill Virtual Machine 
I'm hoping this updated version will keep it going into the future on modern machines!

