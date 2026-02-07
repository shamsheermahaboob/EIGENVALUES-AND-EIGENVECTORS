# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
```
import numpy as np


A = np.array([[4, 2],
              [2, 4]])


eigen_values, eigen_vectors = np.linalg.eig(A)

print("Eigen values are [6. 2.] and Eigen Vectors are",(eigen_vectors))
```

## Output:
<img width="1920" height="1200" alt="Screenshot 2026-02-05 094555" src="https://github.com/user-attachments/assets/d6cfe977-b3c8-4b6d-a37e-cad96eaeae33" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
