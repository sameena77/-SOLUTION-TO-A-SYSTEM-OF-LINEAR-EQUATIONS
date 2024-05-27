# Exp:1 -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
# DATE:02/03/2024
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
```
Developed by:SAMEENA J 
RegisterNumber:2305002019  

`````
```python
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B=np.array([-9,4,-1])
solu=np.linalg.solve(A,B)
print(solu)
```


## Output:
![Screenshot (51)](https://github.com/sameena77/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/155620541/408a078d-0ac4-4668-8427-14167e73506a)






## Result: 
Thus the solutions for the linear equations are successfully solved using python program

