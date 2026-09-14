# 1.Design-implement-and-simulation-of-Inverting-noninverting-and-Differential-amplifier

**AIM:**
To design , implement and simulate  an inverting, non- inverting and differential amplifiers

**APPARATUS  and SOFTWARE REQUIRED:**
S.No	Name of the Apparatus	Range	Quantity
1.	Function Generator	3 MHz	1
2.	DSO	30 MHz	1
3.	Dual RPS	(0 – 30) V	1
4.	Op-Amp	µA741	1
5.	Bread Board		1
6.	Resistors	1K,10K	2
7.	Connecting wires and probes	As required	
8.  LT SPICE software

**THEORY:**
Op-amp in open-loop configuration has a very few application because of its enormous open-loop gain. Controlled gain can be can be achieved by taking a part of output signal to the input with the help of feedback. This is called as Closed- Loop Configuration. The three basic types of closed-loop amplifier configuration are:
1.	Inverting amplifier.
2.	Non-inverting amplifier.
3.	Differential amplifier.
The entire configuration can be operated with either AC or DC input.

**INVERTING AMPLIFIER:**
This is the most widely used op-amp. Here, the output voltage Vo is feedback to the inverting input terminal through the Rf – R1 network. The negative sign in gain indicates the phase shift of 180ο.
The circuit closed-loop voltage gain is Avcl= -RF / R1

**NON - INVERTING AMPLIFIER:**
If signal is applied to the non-inverting input terminal of op-amp without inverting the input signal such a circuit is called non-inverting amplifier. Here the output is feedback to the inverting input terminal. The phase shift of input signal does not occur in non-inverting terminal.
The circuit closed-loop voltage gain is ACL = 1 + ( RF / R1)

**DIFFERENTIAL AMPLIFIER**
A circuit that amplifies that amplifies the difference between two input signals is called as differential amplifier. It is useful in instrumentation amplifier. If the two input signals are the same, the output should be zero. Differential amplifier with a single op-amp has the exact gain of an inverting amplifier and it is given as
𝐴	= 	𝑉𝑜/(V2-V1) = −𝑅𝑓/R1

**DESIGN:**

**Inverting amplifier:**
    Gain is     A = -Rf/R1
        Take  A = 10
        Rf =10 R1
        Choose R1 = 1kΩ, Rf=10kΩ
        
**Non inverting amplifier:**
    Gain is    A = 1+ Rf/R1
      Take A = 2
      Rf = R1
      Choose Rf = 10kΩ, R1=10kΩ
      
**Differential amplifier**
  Gain is 𝐴=	𝑉𝑜/(𝑉1− V2)= − 𝑅𝑓/𝑅1
Take  A = 10
 Rf =10 R1
Choose R1 = 1kΩ, Rf=10kΩ

**PROCEDURE:**
**Inverting and Non-inverting amplifier:**
1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1& compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
   
** Differential amplifier:**
1.	Select the value of R1, R2, R3 & Rf such that R1=R2 and R3=Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Provide constant input voltage Vin1 to Non-inverting terminal of op-amp through R1 & constant input voltage Vin2 to inverting terminal of op-amp through R2.
4.	Measure the output voltage using DSO.
5.	Calculate the theoretical Vo and compare it with practical Vo.
6.	Practical output & theoretical calculation should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
 
**PIN DIAGRAM:**

<img width="623" height="293" alt="image" src="https://github.com/user-attachments/assets/a6910844-6f43-4795-8e49-5af96fbb0596" />


**INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM**
  
  <img width="776" height="378" alt="image" src="https://github.com/user-attachments/assets/2faabc37-51ec-487b-8706-a33138048251" />



  **MODEL GRAPH:**
  
<img width="532" height="372" alt="image" src="https://github.com/user-attachments/assets/120c5c43-9ab2-4e63-b090-28c9229b6868" />


  **TABULATION:**
  
  <img width="900" height="1600" alt="WhatsApp Image 2026-09-13 at 6 25 07 PM (5)" src="https://github.com/user-attachments/assets/11d4aa4d-9bfd-4e0e-b75c-72acf90770d5" />

 

**MODEL CALCULATION:**

**NON INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM**
  
  <img width="733" height="340" alt="image" src="https://github.com/user-attachments/assets/f9f191d7-546c-4a50-a675-8d92ebf942bd" />



  **MODEL GRAPH:**
  
<img width="467" height="306" alt="image" src="https://github.com/user-attachments/assets/41a15669-0c06-44cb-af40-a0038b01f6f5" />


  **TABULATION:**

  <img width="900" height="1600" alt="WhatsApp Image 2026-09-13 at 6 25 07 PM (6)" src="https://github.com/user-attachments/assets/693cb696-da47-4236-a37b-72f6313449d5" />


  **DIFFERENTIAL AMPLIFIER:**
  **CIRCUIT DIAGRAM**
  
<img width="748" height="442" alt="image" src="https://github.com/user-attachments/assets/30c981ed-fe57-41bd-b9dc-d299e29e3ee9" />


  **MODEL GRAPH:**
  
<img width="722" height="315" alt="image" src="https://github.com/user-attachments/assets/44269c6a-e557-49e2-866f-773f2da6c114" />


  **TABULATION:**

  <img width="900" height="1600" alt="WhatsApp Image 2026-09-13 at 6 25 07 PM (7)" src="https://github.com/user-attachments/assets/c1ea7ef7-09c2-4094-b1af-d262b6aad70d" />

  **Graph**


<img width="900" height="1600" alt="WhatsApp Image 2026-09-13 at 6 25 08 PM (2)" src="https://github.com/user-attachments/assets/7276a6b8-5ba9-4f6e-a663-58a87e5fd714" />
<img width="900" height="1600" alt="WhatsApp Image 2026-09-13 at 6 25 07 PM (8)" src="https://github.com/user-attachments/assets/e1de1b9e-2178-4308-b31e-ebcdb981f9af" />




**LT-SPICE Tool:PROCEDURE:**
•	Double click on LT-Spice icon.
•	New schematic window open.
•	Pick and paste the required component from the library and draw the circuit diagram .
•	Complete the connection.
•	Save the file by giving file name.
•	Click on the run option ->click advanced open ->select Ac analysis->enter the amplitude time delay stop time value.
•	Click on the run option ->simulation window opens->place the probe ->output graph is obtained.
 
  **LT SPICE**
  **CIRCUIT and Waveform**

  <img width="900" height="1600" alt="WhatsApp Image 2026-09-13 at 6 25 11 PM (3)" src="https://github.com/user-attachments/assets/7ea90de0-44cf-47e9-ba72-e3e4786aaba4" />
<img width="900" height="1600" alt="WhatsApp Image 2026-09-13 at 6 25 11 PM (2)" src="https://github.com/user-attachments/assets/1fed19f9-32a2-46c5-b45f-e1dc8e6d23c3" />
<img width="900" height="1600" alt="WhatsApp Image 2026-09-13 at 6 25 10 PM (2)" src="https://github.com/user-attachments/assets/5f0d700b-5b28-4457-93b7-f0e020c175d1" />

  

**RESULT:**
Thus the Inverting, Non-Inverting and Differential Amplifiers are designed and simulated performance was successfully tested using op-amp IC 741 and LT SPICE.
 






