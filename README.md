# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure






## Program:
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: swetha.m 
RegisterNumber: 23003160 
*/
![Screenshot 2024-01-03 080401](https://github.com/swetha23003160/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150416143/c3ab63ed-7869-4037-86bf-8f7a7c1095df)




## Truthtable:
halfsubractor
![Screenshot 2024-01-03 080421](https://github.com/swetha23003160/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150416143/9445dab1-656a-40ba-8b67-282c2401feda)

fullsubractor
![Screenshot 2024-01-03 080427](https://github.com/swetha23003160/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150416143/faa5644f-e643-4fc0-ae6f-9c737f14a5cd)



##  RTL realization
halfsubractor
![Screenshot 2024-01-03 080410](https://github.com/swetha23003160/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150416143/dcaed88d-38f0-4c96-a27b-f23c8f39f27f)

fullsubractor
![Screenshot 2024-01-03 080415](https://github.com/swetha23003160/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150416143/7d76e95f-a655-4c1c-bede-3d50d7ba1a79)

## Timing diagram 

![Screenshot 2024-01-03 080436](https://github.com/swetha23003160/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/150416143/495b061e-0204-4ffd-8cbc-9e4fcda0f072)


## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
