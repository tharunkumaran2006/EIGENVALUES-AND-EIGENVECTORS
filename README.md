# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array() 
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
End the program. 

## Program:
```#Program to find the eigen values and eigen vectors.
import numpy as np
A = np.array([[-2, 2, -3],
              [2, 1, -6],
              [-1, -2, 0]])
eigenvalues, eigenvectors = np.linalg.eig(A)
print("Eigen values are [{:.0f}.  {:.0f}. {:.0f}.] and Eigen Vectors are [{}".format(eigenvalues[0],eigenvalues[1],eigenvalues[2],eigenvectors[0]))
print(" [ {:.8f}  {:.8f}  {:.8f}]\n {}]".format(eigenvectors[1][0],eigenvectors[1][1],eigenvectors[1][2],eigenvectors[2]))
#Developed by: Tharun V k
#RegisterNumber:212223230231
```

## Output:
![alt text](<Screenshot 2024-04-10 183515.png>)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
