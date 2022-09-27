# 4-Bit-ALU
# Course

EE227	Digital Logic Design <br />

# Introduction

An Arithmetic-Logic Unit (ALU) is used to perform the arithmetic and logic operations on the operands. A 4 Bit ALU can performs all the 16 different logic and arithmetic operators on two variables which are addition, subtraction and comparator etc. <br />

# Basic Working

Actually it take two variables in the 4 bit and perform three operations which are: <br />
1. Addition <br />
2. Subtraction <br />
3. Comparison <br />

It will perform all the three different operations in a one single circuits and display the output in the LED Screen. <br />

# APPAUTUS: 

1. AND gate <br />
2. OR gate <br />
3. NOT gate <br />
4. NOR gate <br />
5. XOR gate <br />
6. Logic Probe <br />
7. Logic Toggle <br />
8. 7-Segmant BCD  <br />
9. LED Light <br />
10. Ground <br />

# Implementation:
My circuit of the 4 Bit ALU is very basic. I used the very simple logic gate like AND, OR and NOT gate to execute the output of my circuit. I have my task in two parts. One is <br />

1.	Addition and Subtraction <br />

And another is <br />

2. 	Comparator <br />

Addition and Subtraction: <br />
<br />
This task is also divided into the two different tasks which are addition and subtraction. <br />
<br />
Addition: <br />
<br />
For Addition, I take a 4 bit two input and divided it into the four group so that it will perform the task in the one bit operator. And I also made the full adder for each group. I used the two XOR gates for the sum. In the first XOR gate, we take a 0 and B as the input of the first XOR. The output of the first XOR and B is used as the input of the second XOR. Now to check the carry, we will use a two AND gate and one OR gate. The output of the first XOR and 0 is the output of the first AND gate and the output of the second XOR and 0 is the output of the second AND gate. The output of the both AND gate is the input of the OR gate. The result will show that there was a carry or not and utilizers them into the next full adder.   When the last carry is out, the result will show into the 7 Segment BCD. <br />
<br />
Subtraction: <br />
<br />
For Subtraction, I will take a 4 bit binary and used it. with the same logic gates. But this time, we will take a carry input to use as a selection button. The processor for the subtraction in the circuit is same as I explain in the above part. Only the differences between them is the switch. <br />
<br />

Note: When the addition is perform, the switch will be 0 and when the subtraction is perform, the switch will be 1. <br />

Comparator: <br />

For Comparator, l will take a 4 bit two inputs and divided into four groups so that it will perform the task in the one bit operator. There are three conditions on which I created a circuit to check the conditions that which condition is true and which condition are false. These condition are: <br />
1. A > B <br />
2. A = B <br />
3. A < B <br />

To check the equality, I will used the AND gate the NOR gate and the output is used as the input of the OR gate. Then all the four OR gate output is used as the input into the AND gate to check the equality. <br />





