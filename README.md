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

Developed by:TAMILSELVI P
RegisterNumber:25017628

module boolean (


    input  wire A,

    
    input  wire B,

    
    input  wire C,

    
    input  wire D,

    
    output wire F

    
);

assign F = (~A & B) | (C & D) | (A & ~D);


endmodule

**RTL realization**
<img width="1060" height="693" alt="Screenshot (101)" src="https://github.com/user-attachments/assets/d4fb02fb-4110-4b30-8655-c0845532ca80" />

**Output:**
<img width="1097" height="240" alt="Screenshot (102)" src="https://github.com/user-attachments/assets/9f489bcc-182b-49d4-9a7c-ec384d8f58ad" />

**RTL**

**Timing Diagram**

Result:

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

