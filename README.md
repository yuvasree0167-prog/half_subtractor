# Half_subtractor
AIM:

To design a half subtractor circuit and verify its truth table in Quartus using Verilog programming.

Equipments Required:

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime Half Subtractor

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.

Diff = A’B+AB’ =A ⊕ B Borrow = A’B

<img width="693" height="321" alt="Screenshot 2025-12-14 220911" src="https://github.com/user-attachments/assets/d2eb0c2d-7ebc-45d0-b802-697d498b3e5d" />


Truthtable

<img width="339" height="160" alt="Screenshot 2025-12-14 221453" src="https://github.com/user-attachments/assets/f52f83d3-5871-4bd4-98ba-c711838b731a" />


Procedure

1.Type the program in Quartus software.

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for inputs and outputs to generate the timing diagram.

5.For different input combinations generate the timing diagram.

Program:

/* Program to design a half subtractor circuit and verify its truth table in quartus using Verilog programming.

Developed by:YUVASREE S RegisterNumber:25014102*/

RTL Schematic

Output/TIMING Waveform

Result:Thus, the Half subtractor circuits are designed and the truth tables is verified using Quartus software.
