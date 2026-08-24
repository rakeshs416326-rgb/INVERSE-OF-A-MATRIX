# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step1 :
Import the numpy module to use the built-in functions for calculation

## Step 2:
Prepare the lists from each linear equations and assign in np.array()

## Step 3:
Using np.linalg.inv(),we can find the inverse of a matrix

## Step 4:
End the program

## Program:
# Linear Algebra Exp 3
```
Write a python program to find the inverse of the given matrix
 1 0  3
-1 2 -2
 2 3 -1
```
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
b=np.linalg.inv(a)
print(b)
```

## Output:
<img width="1047" height="770" alt="image" src="https://github.com/user-attachments/assets/50025ebd-7c01-45cc-915f-e4d2b3a0b59a" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

