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


 ![image](/![Screenshot 2023-11-25 120148](https://github.com/premsuryas/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147473858/4b6660b6-2d2f-4bc7-8118-3dfae6b9c38a)
.png)

#### Figure -01 HALF ADDER 


![image](![Screenshot 2023-11-25 114302](https://github.com/premsuryas/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147473858/9f88374e-8be4-406a-9804-d6e0cb25b4e8)
.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
/*half adder
module ha(a,b,sum,carry);
input a,b;
output sum,carry;
xor(sum,a,b);
and(carry,a,b);
endmodule
/*full adder
module ha(a,b,c,sum,carry);
input a,b,c;
output sum,carry;
assign sum = ((a^b)^c);
assign carry = ((a&b) | (b&c) |(c&a));
endmodule
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by:PREM KUMAR 
RegisterNumber:23013598  
*/
Logic symbol & Truthtable
RTL realization

### Output:
### RTL
### TIMING DIAGRAM

![Screenshot 2023-11-25 114931](https://github.com/premsuryas/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147473858/aa0cb80a-3597-40c6-86ab-e6d7937a8d8a)



### TRUTH TABLE 

![half adder truth table](https://github.com/premsuryas/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147473858/2d1462f9-4b28-4361-bddb-2a52d23c3661)


### Result:
THE HALF ADDER AND FULL ADDER WAS CREATED SUSCESSFULLY
