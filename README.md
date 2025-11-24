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
module boolean_function_4var (
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule
```

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming.

<img width="441" height="293" alt="Screenshot 2025-11-18 210546" src="https://github.com/user-attachments/assets/2ed8c00d-20b9-4fba-8c39-7857b77793b7" />


Developed by: PERARASU K RegisterNumber: 25004665


**RTL realization**

<img width="1020" height="630" alt="Screenshot 2025-11-18 205759" src="https://github.com/user-attachments/assets/5a3ade0f-ed9f-4b9b-9f9f-4a15ac293104" />


**Output:**

**RTL**

**Timing Diagram**

<img width="1319" height="247" alt="Screenshot 2025-11-24 080728" src="https://github.com/user-attachments/assets/a42ebc6a-6858-440d-98b7-5f324b67a860" />



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

