# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: S R SHIV SUHAN

RegisterNumber:  23004611

Code:

Half Adder:


![Exp3 ha code](https://github.com/shivsujan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145633245/cdc9cf90-89d2-43cf-bd1e-e02c2cbd5e9a)

Full adder:

![Exp3 fa code](https://github.com/shivsujan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145633245/5c3ff967-816a-4248-959e-e34c3618aced).

Truth Table:

Half Adder:

![Exp3 truthtable (ha)](https://github.com/shivsujan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145633245/a1fb2205-5f1c-4112-82b0-13fd99895b8c)

Full Adder:


![Exp3 truthtable (fa)](https://github.com/shivsujan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145633245/9bd98778-c888-43ec-97d6-99dd39ab7ec6)

RTL Diagram :

Half Adder:

![Exp3 ha RTL diagram](https://github.com/shivsujan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145633245/ea718893-9fbe-4d89-ae30-eb721146fa46)

Full Adder:

![Exp3 fa RTL diagram](https://github.com/shivsujan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145633245/662a0dba-0ca9-47eb-b418-9cb9f6c27d60)


### Output:

Half Adder:

![halfadder-wave](https://github.com/shivsujan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145633245/e96e3c84-e90e-43cc-a0f3-564cc68f81f8)

Full Adder:

![Exp3 fa wave](https://github.com/shivsujan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/145633245/55d41059-d3ee-4f10-9976-d2356ec0043a)

### Result:
Thus the half adder and full adder circuit are designed and the truth table for half adder and full
adder are verified
