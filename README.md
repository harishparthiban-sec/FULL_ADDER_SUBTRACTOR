# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
<img width="708" height="247" alt="image" src="https://github.com/user-attachments/assets/e376ce81-4d01-45f3-aee4-7b61ff8e65c9" />
<img width="708" height="247" alt="image" src="https://github.com/user-attachments/assets/44472d4b-a38b-4062-a7be-a77059ab0ab0" />

Developed by: Harish P RegisterNumber:25015017
*/

**RTL Schematic**
<img width="1023" height="712" alt="image" src="https://github.com/user-attachments/assets/cb42b861-0d28-4733-a144-2a150150a25a" />
<img width="1015" height="488" alt="image" src="https://github.com/user-attachments/assets/f9bafb4a-4e5c-490a-9a95-79be5be0aaa0" />

**Output Timing Waveform**
<img width="1302" height="372" alt="image" src="https://github.com/user-attachments/assets/ceca97b2-5e6f-474b-93bb-3ba43b48ec36" />
<img width="1280" height="341" alt="image" src="https://github.com/user-attachments/assets/971b1d39-9731-4a45-975e-f5c0d5961814" />

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



