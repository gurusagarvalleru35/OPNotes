Fuzzing : send mal-formed data to the application , if application doesn't filter the input correctly. This might lead to crash .  
Executable space protecion  is called Data Execution Prevention 
Address Space Layout Randomization in preventing expolitation of memory corruption vulnerabilities . 

Registers :

Refer:  https://upload.wikimedia.org/wikipedia/commons/thumb/1/15/Table_of_x86_Registers_svg.svg/2000px-Table_of_x86_Registers_svg.svg.png

ESP : Extended Stack Pointer
EIP : Extended Instruction Pointer 

Immunity Debugger 

Crashing the application with a fuzzer crash 

Binary Tree Analysis
sending unique string 
pattern create , pattern offset 

Locating space for your shell code - reverse shell payload requires about 350 - 400 bytes of space.

Checking for bad characters 0x00 to 0xff
 0x00 - null byte 
 0x0A - line feed 
 0x0D - carriage return 

Redirecting the execution flow 

Finding a Return address mona.py modules 
JMP ESP 

Metasploit nasm shell  nasm_shell.rb 

x86 architecture stores addresses in little endian format

Generating Shellcode with metasploit 

msfvenom syntax for reverse shell payload and remove bad chars 

Getting a shell - add few No Operation instructions (NOP) (0x90) at the beginning of our shell code . 

Improving the Exploit -- ExitProcess

Linux BO :

Stack Smashing protection support , ASLR , and DEP support 

Evans Debugger

Controlling EiP : pattern_create , pattern_offset 

Finding Space for Our Shellcode

Improving Exploit Reliability 

Discovering Bad characters - x00, x0A, x0D, x20

Finding a return address - evan debugger has opcode search feature . 

Getting a shell 

Working with exploits 

Searching : 
 finding exploits in kali ( searchsploit )
 finding exploits on the web 

Customizing and Fixing Exploits 

Setup Dev Env 
Dealing with various Exploit code languages
swapping out shell code 
