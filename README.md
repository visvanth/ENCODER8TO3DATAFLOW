# EX NO:5
<P align='center'> <b>ENCODER 8TO3 DATAFLOW Modelling</b>

**DATE:**

**AIM:**

To implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:** Quartus prime

**THEORY**

**Encoder 8 To 3**

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/0bc242c1-eb9e-4c47-afe5-30428470efc3)

Figure 01  Block Diagram of Encoder 8 * 3

**Truth Table**

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/35496b14-ae6e-4cd1-9abd-d6736b576575)

The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/95acaee6-c873-4c75-89eb-ef09fb158053)

Figure 02  Encoder 8 * 3

**Procedure**
1.Type the program in Quartus software.

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for inputs and outputs to generate the timing diagram.

5.For different input combinations generate the timing diagram.

**Program for Encoder 8 To 3 in Dataflow Modelling and verify its truth table in quartus using Verilog programming.** 

**Developed by:VISVANTH PS**

**RegisterNumber:212223050061**

**PROGRAM**

![Screenshot 2024-04-27 115000](https://github.com/karuniya2005/ENCODER8TO3DATAFLOW/assets/161425769/6b4ab7a6-cffa-46c0-9de1-2e0f350ab874)



**RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling**

![Screenshot 2024-05-01 203010](https://github.com/karuniya2005/ENCODER8TO3DATAFLOW/assets/161425769/f3f7fdcf-0d03-4d6e-8743-a0edc59848c2)


**TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling**

![Screenshot 2024-05-01 203021](https://github.com/karuniya2005/ENCODER8TO3DATAFLOW/assets/161425769/75c5df0e-6de4-4aa9-a078-817b6b73ed89)


**RESULTS**

Thus, an 8*3 encoder has been implemented using verilog successfully.




