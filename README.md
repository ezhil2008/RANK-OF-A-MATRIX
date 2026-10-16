# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
import the os and numpy as py and type os.environ["OPENBLAS_NUM_THREADS"]="1"
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
print the rank of the matrix and end the program
## Program:
#Program to find the rank of a matrix.
#Developed by:Ezhil Nilavan E
#RegisterNumber:26018188
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[3,2,5],[1,1,2],[3,3,6]])
r=np.linalg.matrix_rank(a)
print(r)
## Output:
<img width="397" height="151" alt="Screenshot From 2026-10-16 08-31-58" src="https://github.com/user-attachments/assets/8addb498-933f-4dfb-ae3e-4fc688a69c7f" />
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

