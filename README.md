# EXPERIMENT 3: Simulation of All Flip-Flops using Blocking Statement

## AIM
To design and simulate basic flip-flops (SR, D, JK, and T) using **blocking statements** in Verilog HDL, and verify their functionality through simulation in Vivado 2023.1.

## APPARATUS REQUIRED
- Vivado 2023.1
- Computer with HDL Simulator

## DESCRIPTION
Flip-flops are the basic memory elements in sequential circuits.  
In this experiment, different types of flip-flops (SR, D, JK, T) are modeled using **behavioral modeling** with **blocking assignment (`=`)** inside the `always` block.  
Blocking assignments execute sequentially in the given order, which makes it easier to describe simple synchronous circuits.

## PROCEDURE
1. Open **Vivado 2023.1**.  
2. Create a **New RTL Project** (e.g., `FlipFlop_Simulation`).  
3. Add Verilog source files for each flip-flop (SR, D, JK, T).  
4. Add a testbench file to verify all flip-flops.  
5. Run **Behavioral Simulation**.  
6. Observe waveforms of inputs and outputs for each flip-flop.  
7. Verify that outputs match the truth table.  
8. Save results and capture simulation screenshots.

---

## VERILOG CODE

### SR Flip-Flop (Blocking)

<img width="1363" height="698" alt="image" src="https://github.com/user-attachments/assets/8356ee68-211e-48ad-b54c-f9353bdb512b" />

### SR Flip-Flop Test bench 

<img width="1367" height="701" alt="image" src="https://github.com/user-attachments/assets/f1b6f0b3-f6b2-4279-9a71-eb71ebfc5ef3" />


#### SIMULATION OUTPUT

<img width="1355" height="702" alt="image" src="https://github.com/user-attachments/assets/9211731f-1bb8-42da-9b99-7c044d5cea94" />


### JK Flip-Flop (Blocking)

<img width="1354" height="697" alt="image" src="https://github.com/user-attachments/assets/caa43352-0faa-479c-ad66-a36d215f395c" />

### JK Flip-Flop Test bench 

<img width="1360" height="700" alt="image" src="https://github.com/user-attachments/assets/c62b2673-13d3-4ec4-bd9e-725832e394cc" />


#### SIMULATION OUTPUT

<img width="1351" height="698" alt="image" src="https://github.com/user-attachments/assets/54d646a1-c01d-4e86-b62a-b96a05ca0be3" />


### D Flip-Flop (Blocking)

<img width="1355" height="708" alt="image" src="https://github.com/user-attachments/assets/185b3138-20c4-458d-bbe7-544c02968f28" />


### D Flip-Flop Test bench 


<img width="1358" height="695" alt="image" src="https://github.com/user-attachments/assets/bd520fb2-57ec-4edb-8c63-285747218958" />


#### SIMULATION OUTPUT

<img width="1364" height="697" alt="image" src="https://github.com/user-attachments/assets/3efb8c09-add7-423b-8e68-23ef0b879743" />

### T Flip-Flop (Blocking)

<img width="1342" height="706" alt="image" src="https://github.com/user-attachments/assets/2746c60c-ae6b-4bd7-a853-f3cfdfaf0d52" />



### T Flip-Flop Test bench 


<img width="1359" height="695" alt="image" src="https://github.com/user-attachments/assets/6c47543d-5609-46d1-8e46-36e823448278" />


#### SIMULATION OUTPUT

<img width="1354" height="716" alt="image" src="https://github.com/user-attachments/assets/2fc90804-2177-4a45-848c-ea30c969ffc0" />

### RESULT

All flip-flops (SR, D, JK, T) were successfully simulated using blocking statements in Verilog HDL.
The outputs matched the expected truth table values, demonstrating correct sequential behavior.
