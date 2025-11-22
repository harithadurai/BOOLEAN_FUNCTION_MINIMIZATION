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

```
module funct1(a,b,c,d,f1); 
input a,b,c,d; 
output f1; 
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c)); 
endmodule 
```



Developed by:D.Haritha
RegisterNumber:25017580


**RTL realization**


<img width="1920" height="1080" alt="Screenshot 2025-11-22 161947" src="https://github.com/user-attachments/assets/09518c94-6e87-4eac-afa5-a9ac842db4c7" />



**RTL**

<img width="1920" height="1080" alt="Screenshot (19)" src="https://github.com/user-attachments/assets/29ffd28e-4448-462c-8b27-bc6b88632354" />

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming is verified successfully.

