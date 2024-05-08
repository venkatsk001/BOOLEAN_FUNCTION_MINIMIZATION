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
module exp22(A,B,C,D,F1);
input A,B,C,D;
output F1;
wire x1,x2,x3,x4,x5;
assign x1=(~A)&(~B)&(~C)&(~D);
assign x2=(A)&(~C)&(~D);
assign x3=(~B)&(C)&(~D);
assign x4=(~A)&(B)&(C)&(D);
assign x5=(B)&(~C)&(D);
assign F1=x1|x2|x3|x4|x5;
endmodule


Developed by:BHARATH.N Register no:212223230030


**RTL realization**
![image](https://github.com/moulidharyadav/BOOLEAN_FUNCTION_MINIMIZATION/assets/147078316/05234e26-2b4c-47b5-8d8b-e63daa922469)


**Output:**

**RTL**![image](https://github.com/moulidharyadav/BOOLEAN_FUNCTION_MINIMIZATION/assets/147078316/615e0f28-6e8c-458f-b12d-5c3472366a86)

**Timing Diagram**
![image](https://github.com/moulidharyadav/BOOLEAN_FUNCTION_MINIMIZATION/assets/147078316/ba4880f3-97a8-4bef-bc53-1d2ca795fba8)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

