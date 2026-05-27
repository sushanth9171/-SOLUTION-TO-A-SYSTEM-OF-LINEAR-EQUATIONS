# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:

#Program to find the solution for the given linear equations.  
#Developed by: G.Sushanth  
#RegisterNumber:212225230088  
import numpy as np  
a=np.array[[1,3],[2,5]]  
b=np.array([5,-3])  
result=np.linalg.solve(a,b)  
print(result)  

## Output:
<img width="770" height="575" alt="{706E8C83-B42C-4F78-A975-94E8E7F64471}" src="https://github.com/user-attachments/assets/ac3e6dc1-4f8f-4352-a643-b36d08b3da56" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

