# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy as np
### Step 2: 
Assign np.linalg.eig() in eigen values and eigen vectors.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
print both the values and vectors, then end the program.

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: SANJAY M
#RegisterNumber:212223230187

import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors =np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![Screenshot 2024-03-09 094316](https://github.com/sanjayofficial2005/EIGENVALUES-AND-EIGENVECTORS/assets/148048602/5a2241d3-c777-4e77-a3f0-55572cd8f6d7)
![Screenshot 2024-03-09 094325](https://github.com/sanjayofficial2005/EIGENVALUES-AND-EIGENVECTORS/assets/148048602/99e92d55-9a1c-4e96-b861-b9aacf03fa72)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
