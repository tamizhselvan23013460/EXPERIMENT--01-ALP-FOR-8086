# EXPERIMENT--01-ALP-FOR-8086
```
Name :TAMIZHSELVAN B
Roll no : 212223230225
Date of experiment : 10/03/2025
```

## Aim:
To Write and execute ALP on fundamental arithmetic and logical operations
## Components required:
8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
3.	write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 
4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 
6.	Click OK to see/view the output of your program on the Emulator screen. 
7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,

   
![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)


8.	Click on emulate to start emulation 


![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)


9.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 

![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)


## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
Mov AL,74H
Mov BL,69H
ADD AL,BL
HLT
```
## Output  

![ALP_ADD_OUTPUT](https://github.com/user-attachments/assets/3b42a7e8-30e1-40c9-be44-e4547b44561c)

## Subtraction   of 8 bit numbers  ALP 
```
Mov AL,74H
Mov BL,69H
SUB AL,BL
HLT
```
## Output :

![ALP_SUB_OUTPUT](https://github.com/user-attachments/assets/4e3d4c0c-f4da-4e15-9f7c-99e4e3a628e0)


## Multiplication alp :
```
org 100H
Mov AL,75H
Mov BL,32H
MUL BL
HLT 
ret
```
 ## Output  :

 ![ALP_MUL_OUTPUT](https://github.com/user-attachments/assets/a40ae261-4a38-4a42-b83d-39602db1f850)

## Division alp :
```
org 100H
Mov AL,68H
Mov BL,18H
DIV BL
HLT 
ret
```
## Output  :

![ALP_DIV_OUTPUT](https://github.com/user-attachments/assets/83703aac-48c9-4028-8458-c0261b7c6dcf)


## Programs for Logical operations:

## AND alp :
```
MOV AL,33H
MOV BL,44H
AND AL,BL
HLT
```

## Output:

![ALP_AND_OUTPUT](https://github.com/user-attachments/assets/8f3e7190-9498-4036-92d0-36544d1a27f8)

## NOT alp :
```
MOV AL,65H
NOT AL
HLT
```

## Output:

![ALP_NOT_OUTPUT](https://github.com/user-attachments/assets/1d76be5c-e582-4e54-bcba-679f33eeb83a)

## OR alp :
```
MOV AL,33H
MOV BL,44H
OR AL,BL
HLT
```

## Output :

![ALP_OR_OUTPUT](https://github.com/user-attachments/assets/9026cac4-c94a-4006-92db-caecf215ce2f)


## XOR alp :

```
ORG 100H
MOV AL,66H
MOV BL,77H
XOR AL,BL
HLT
RET
```

## Output :

![ALP_XOR_OUTPUT](https://github.com/user-attachments/assets/f9247015-68a0-43a3-87dd-af858fa0d9be)


## Result :

The execution of ALP on fundamental of arithmetic and logical operation is successfully completed. 







