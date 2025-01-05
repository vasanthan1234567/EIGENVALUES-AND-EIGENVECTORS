# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation

### Step 2:
Prepare the lists from each linear equations and assign in np.array()

### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 
End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: vasanthan N
#RegisterNumber: 24900250
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
e_va,e_ve=np.linalg.eig(A)
print(f"Eigen values are {e_va} and Eigen Vectors are {e_ve}")


```
## Output:
![output](<Screenshot 2025-01-05 153928.png>)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
