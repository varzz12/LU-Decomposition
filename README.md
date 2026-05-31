# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the required NumPy and SciPy libraries.
2. Get the matrix elements from the user and store them in a matrix form.
3. Use the scipy.linalg.lu() function to perform LU Decomposition of the given matrix.
4. Display the Lower triangular matrix (L) and Upper triangular matrix (U) as the output.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Varuna R
RegisterNumber: 212225040483
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
from scipy.linalg import lu
import ast

A = ast.literal_eval(input())

P, L, U = lu(A)

print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Varuna R
RegisterNumber: 212225040483
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor, lu_solve
import ast

A = ast.literal_eval(input())
B = ast.literal_eval(input())

lu, piv = lu_factor(A)
X = lu_solve((lu, piv), B)

print(X)

*/
```

## Output:
![lu decomposition]()
<img width="1234" height="597" alt="image" src="https://github.com/user-attachments/assets/9d0c2804-2160-4d56-b0bc-503abd07cc2f" />
<img width="1225" height="336" alt="image" src="https://github.com/user-attachments/assets/cd47271b-a0b5-4bd2-9341-9be3d1c433b8" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

