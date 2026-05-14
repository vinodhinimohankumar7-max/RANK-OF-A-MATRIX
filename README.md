# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the NumPy library to perform matrix operations in Python.
### Step 2: Define the matrix elements using a list or array format.
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Display the obtained rank using the print() function.
## Program:
```
#Program to find the rank of a matrix.
#Developed by: vinodhini M K
#RegisterNumber:212225230305
#Program to find the rank of a matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[3,2,5],[1,1,2],[3,3,6]])
solution=np.linalg.matrix_rank(a)
print(solution)
```
## Output:
![alt text](<Screenshot 2026-05-14 113844.png>)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

