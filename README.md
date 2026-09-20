# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import numpy as np
### Step 2: create a matrix using numpy
### Step 3: Using the np.linalg.eig(),  we get two results [First is eigenvalue and second is eigenvector] of the given matrix.
### Step 4: End the Program
## Program: #Developed by: : K.sundar
#RegisterNumber:212225040438
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=np.array([[4,2],[2,4]])

eigenvalues,eigenvectors =np.linalg.eig(matrix)

print("Eigen values are {} and Eigen Vectors are {}".format(eigenvalues,eigenvectors ))

```
## Output:
<img width="1266" height="787" alt="image" src="https://github.com/user-attachments/assets/df8d838e-37de-4dd0-be8a-9afb28fcd7b3" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
