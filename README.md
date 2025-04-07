# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:Vaishak.M

RegisterNumber:212224040355

**Ex 2A

module exp2(a,b,c,d,F1);

input a,b,c,d;

output F1;

assign F1=((~a&b&d)|(~b&~d)|(a&b&~c));

endmodule 

**Ex 2B

module EXP2B(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2= ((~y&z)|(w&z)|(x&y)|(w&y&~z));

endmodule



**RTL realization**

EXP 2A

![exp2](https://github.com/user-attachments/assets/50681834-c828-4169-a751-c4c041931d64)

EXP 2B

![Screenshot 2025-04-07 133040](https://github.com/user-attachments/assets/8a1418db-4348-421f-b3b6-af5d39b8d9d8)


**Timing Diagram**

EXP 2A
![Screenshot 2025-04-07 133432](https://github.com/user-attachments/assets/8e757969-9d81-449d-866e-d5b5a95a6aa5)

EXP 2B

![WhatsApp Image 2025-04-07 at 13 34 48_253320eb](https://github.com/user-attachments/assets/111329fa-866e-4e43-8498-d0ae3484e697)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

