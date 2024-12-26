### NAME:JEEVAN VISHAL.G.D.
### REG NO:24900595
###  EXPERIMENT:5: 8TO3 DATAFLOW Modelling

### AIM:

To implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

### SOFTWARE REQUIRED:
Quartus prime

### THEORY:

Encoder 8 To 3

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/0bc242c1-eb9e-4c47-afe5-30428470efc3)

Figure 01  Block Diagram of Encoder 8 * 3

#### TRUTH TABLE:

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/35496b14-ae6e-4cd1-9abd-d6736b576575)

The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/95acaee6-c873-4c75-89eb-ef09fb158053)

Figure 02  Encoder 8 * 3

### PROCEDURE:
Type the program in Quartus software
Compile and run the program.
Generate the RTL schematic and save the logic diagram.
Create nodes for inputs and outputs to generate the timing diagram.
For different input combinations generate the timing diagram.

### PROGRAM:
![Screenshot 2024-12-26 104816](https://github.com/user-attachments/assets/25430261-b567-4649-9f75-dae7be957f4d)

### RTL LOGIC FOR ENCODER 8 TO 3 IN DATAFLOW MODELLING:
![Screenshot 2024-12-26 104249](https://github.com/user-attachments/assets/4290bef3-dc7e-4c0a-9ca6-332df268662e)


### TIMING DIGRAMS FOR ENCODER 8 TO 3 IN DATA MODELLING:
![Screenshot 2024-12-26 104345](https://github.com/user-attachments/assets/14872f63-d7d6-4007-9f90-d1bae009efb6)

### RESULTS:
Hence the code was executed sucessfuly.





