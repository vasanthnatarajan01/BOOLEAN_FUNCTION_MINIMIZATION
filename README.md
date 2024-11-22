# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime:**

**Theory:**
![WhatsApp Image 2024-11-22 at 20 44 29_7e9c8369](https://github.com/user-attachments/assets/17c925ee-533e-4130-b3f0-a30f15b9cd59)

![WhatsApp Image 2024-10-29 at 10 50 38_de9128d1](https://github.com/user-attachments/assets/5e0d3f4d-9571-432f-9d08-a4f5579781ee)



**Procedure:**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: Vasanth N
RegisterNumber: 24000697

module exp_2(a,b,c,d,f1,f2,w,x,y,z);   
input a,b,c,d,w,x,y,z;  
output f1;    
output f2;   
assign f1 = ((~b & ~d)|(~a&b&d)|(a&b&~c));  
assign f2 = ((~y&z)|(x&y)|(w&y));  
endmodule   

**RTL realization Qutput:**
![exp_2](https://github.com/user-attachments/assets/dae66aa9-c290-4d77-b9da-010175b530bd)

**Timing Diagram:**
![exp_2_line](https://github.com/user-attachments/assets/e606ecc1-c747-413a-8f7f-4506ab83238b)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

