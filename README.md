
# EXPERIMENT--04-ARITHMETIC-AND-LOGICAL-OPERATIONS-USING-LADDER-LOGIC
#  NAME: thenmozhi.p
# REGISTER NUMBER: 212223100059
# DEPARTMENT: CSE (cs)
# YEAR: 3rd year
## Aim:
To understand and implement various arithmetic and logical operations in Programmable Logic Controller (PLC) ladder logic.

## Apparatus Required:
Programmable Logic Controller (PLC): A PLC that supports arithmetic and logical functions.
PLC Programming Software: Software such as RSLogix, TIA Portal, or CX-Programmer.
Computer System: For programming and simulating the PLC ladder logic.
Input Devices: Push buttons or switches to trigger arithmetic and logical operations.
Output Devices: LEDs or other indicators to visualize the results of operations.
Wires and Connectors: For interfacing input/output devices with the PLC.
Power Supply: Appropriate power supply for the PLC and peripherals.
## Theory:
Arithmetic and logical operations in PLC ladder logic are essential for handling complex decision-making and calculations within automation processes. Arithmetic operations (e.g., addition, subtraction, multiplication, division) and logical operations (e.g., AND, OR, NOT) allow PLCs to perform calculations, make comparisons, and control actions based on specific conditions.

## Types of Operations:
Arithmetic Operations:

Addition (ADD): Adds two values and stores the result in a specified memory location.
Subtraction (SUB): Subtracts one value from another.
Multiplication (MUL): Multiplies two values.
Division (DIV): Divides one value by another.
Logical Operations:

AND Operation: The output is TRUE only when all inputs are TRUE.
OR Operation: The output is TRUE when any input is TRUE.
NOT Operation: Inverts the input logic.
Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer and launch the PLC programming software.
Ensure all input and output devices are connected to the PLC’s I/O modules.
Create Ladder Logic for Arithmetic Operations:

Addition (ADD):
Create a rung with an input (e.g., push button) linked to an ADD instruction.
Set the operands (e.g., two values) and the destination to store the result.
Subtraction (SUB):
Create a rung with an input linked to a SUB instruction.
Set the values and the destination to store the result.
Multiplication (MUL):
Create a rung with an input linked to a MUL instruction.
Set the values and the destination to store the result.
Division (DIV):
Create a rung with an input linked to a DIV instruction.
Set the values and the destination to store the result.
Create Ladder Logic for Logical Operations:

AND Operation:
Create a rung with two inputs connected in series to simulate an AND operation.
Assign an output to visualize when both inputs are TRUE.
OR Operation:
Create a rung with two inputs connected in parallel to simulate an OR operation.
Assign an output to visualize when any input is TRUE.
NOT Operation:
Create a rung with a single input connected to a NOT function.
Assign an output to visualize the inverted logic.
Simulate the Ladder Logic:

Arithmetic Operations:
Run the simulation in the PLC software. Trigger each operation by pressing the input button, and observe the output values.
Logical Operations:
Simulate the AND, OR, and NOT logic by toggling the inputs and observing the outputs.
Download and Execute:

Download the ladder logic program to the PLC if available and run it.
Test the arithmetic and logical operations with physical push buttons and observe the LEDs or other output devices.


## Outputs:
## Ladder Logic Diagrams :
### ADD
<img width="809" height="174" alt="Screenshot 2025-10-09 090945" src="https://github.com/user-attachments/assets/0917d831-b623-44fd-8e21-79d1c77bf0cc" />

### SUB
<img width="760" height="229" alt="Screenshot 2025-10-09 090958" src="https://github.com/user-attachments/assets/7da7a576-0e2f-4478-bc85-93c3fddb625b" />

### MUL
<img width="778" height="196" alt="Screenshot 2025-10-09 090952" src="https://github.com/user-attachments/assets/b4637a9c-877a-4f09-adb3-51f154675b2b" />

### DIV
<img width="822" height="198" alt="Screenshot 2025-10-09 091003" src="https://github.com/user-attachments/assets/d54feeac-25ee-457e-ad2a-8b896f9f0766" />

### INCREMENT
<img width="786" height="183" alt="Screenshot 2025-10-09 091010" src="https://github.com/user-attachments/assets/eb8587f9-e3c4-4975-8e96-1bb40d05c651" />

### DECREMENT
<img width="697" height="183" alt="Screenshot 2025-10-09 091016" src="https://github.com/user-attachments/assets/b758ec97-d56d-43d0-93f0-533bd269a3c0" />

### AND
<img width="761" height="198" alt="Screenshot 2025-10-09 091021" src="https://github.com/user-attachments/assets/499b3401-63b9-4bf0-aad7-c9efa66807a0" />

### OR
<img width="807" height="220" alt="Screenshot 2025-10-09 091025" src="https://github.com/user-attachments/assets/8540af60-edff-461f-bc65-f7af9f238659" />

### XOR
<img width="851" height="212" alt="Screenshot 2025-10-09 091032" src="https://github.com/user-attachments/assets/a50ef569-f6e8-4338-8cc8-2fdc95ad72fd" />

### NEG
<img width="723" height="196" alt="Screenshot 2025-10-09 091037" src="https://github.com/user-attachments/assets/a03be4fd-8fee-47d3-86a0-9c79a6fb8613" />

### MUL16
<img width="855" height="231" alt="Screenshot 2025-10-09 091043" src="https://github.com/user-attachments/assets/fbf8a1eb-a590-491d-83c3-6806e7cfb66b" />


##  Simulation Screenshots:
### ADD
<img width="1915" height="1072" alt="Screenshot 2025-10-09 090712" src="https://github.com/user-attachments/assets/c8a53f39-797a-4e6a-8d06-6d371d38723c" />

### SUB
<img width="1916" height="1072" alt="Screenshot 2025-10-09 090727" src="https://github.com/user-attachments/assets/de23f1f2-883a-4bfd-aeb9-60a7082ebb46" />

### MUL
<img width="1919" height="1079" alt="Screenshot 2025-10-09 090738" src="https://github.com/user-attachments/assets/bced90a9-b327-4896-8832-2c43f94da288" />

### DIV
<img width="1919" height="1077" alt="Screenshot 2025-10-09 090749" src="https://github.com/user-attachments/assets/e75b3761-41a5-4647-9323-92349e563912" />

### INCREMENT
<img width="1919" height="1079" alt="Screenshot 2025-10-09 090802" src="https://github.com/user-attachments/assets/7a02859d-ef95-4f8c-bdb8-aed5f547b856" />

### DECREMENT
<img width="1919" height="1075" alt="Screenshot 2025-10-09 090813" src="https://github.com/user-attachments/assets/b687e876-923e-426b-b841-08671dad39e4" />

### AND
<img width="1915" height="1074" alt="Screenshot 2025-10-09 090825" src="https://github.com/user-attachments/assets/6602b419-0a3d-4190-962a-342a2a698937" />

### OR
<img width="1919" height="1079" alt="Screenshot 2025-10-09 090835" src="https://github.com/user-attachments/assets/82b410a7-8d87-4117-aae3-14e45380aa05" />

### XOR
<img width="1919" height="1079" alt="Screenshot 2025-10-09 090845" src="https://github.com/user-attachments/assets/ac8c6df4-dc27-4b19-affc-fdd3b14c5714" />

### NEG
<img width="1919" height="1079" alt="Screenshot 2025-10-09 090845" src="https://github.com/user-attachments/assets/b2903e6f-fe7d-4c7b-967e-5edc26332939" />

### MUL16
<img width="1919" height="1079" alt="Screenshot 2025-10-09 090924" src="https://github.com/user-attachments/assets/629ea983-bfc7-4998-9d42-4c972120fa63" />



## Results:
The ladder logic programs for various arithmetic and logical operations were successfully implemented and tested. The outputs were as expected, demonstrating correct calculation and logical decision-making capabilities. This experiment illustrates the essential role of arithmetic and logical functions in automated processes.

