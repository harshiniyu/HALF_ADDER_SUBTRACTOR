# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**

![WhatsApp Image 2024-04-03 at 11 21 12_8664b689](https://github.com/harshiniyu/HALF_ADDER_SUBTRACTOR/assets/144979786/678b3dbf-a998-4b5a-b9ae-21bfa2bad85b)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
**HALF ADDER:**
![image](https://github.com/harshiniyu/HALF_ADDER_SUBTRACTOR/assets/144979786/cf782726-a0aa-4c57-8046-bdb1ef1ea885) 


**HALF SUBTRACTOR:**
![image](https://github.com/harshiniyu/HALF_ADDER_SUBTRACTOR/assets/144979786/2874bd11-bbae-4e70-ada2-ebd5220848f6)


/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by:Harshini Y
RegisterNumber:*/212223240050

**RTL Schematic**

![image](https://github.com/harshiniyu/HALF_ADDER_SUBTRACTOR/assets/144979786/c565b323-7c6b-4be2-85a6-705a33f473cf)


![image](https://github.com/harshiniyu/HALF_ADDER_SUBTRACTOR/assets/144979786/c8c555de-b996-495b-a04f-d4e43c53f24a)





**Output/TIMING Waveform**

![image](https://github.com/harshiniyu/HALF_ADDER_SUBTRACTOR/assets/144979786/d44dac75-8fc4-47be-88fe-88be17aa920d)



![image](https://github.com/harshiniyu/HALF_ADDER_SUBTRACTOR/assets/144979786/f6b42c54-072c-48d8-bad4-3b39391c7adc)



**Result:**
Thus, a half adder and half subtractor circuit is designed to verify its truth table in Quartus using Verilog programming.
