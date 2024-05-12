# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 

Import the numpy module to use the built-in functions for calculation

### Step 2: 

Prepare the lists from each equations and assign in np.array()

### Step 3: 

Using the np.linalg.matrix_rank(), we can find the inverse of the given matrix

### Step 4: 

End the program
## Program:
#Program to find the inverse of a matrix.

#Developed by: SOWMYA BADONI

#RegisterNumber:212223230211

import numpy as np

matrix=np.array([[6,2,3],[3,1,1],[10,3,4]])

result=np.linalg.inv(matrix)

print(result)

## Output:
![Screenshot 2024-05-12 173825](https://github.com/sowmya-badoni/INVERSE-OF-A-MATRIX/assets/152136324/262e6756-53d1-403a-8b7d-f3d7fe3a026b)

## Result:
Thus the inverse of given matrix is successfully solved using python program

