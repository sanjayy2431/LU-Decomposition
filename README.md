# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define the package as scipy.linalg import lu.
2.Get input from user and print L and U matrix by 'print' .
3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4.print the variable 'X'

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: sanjay v
RegisterNumber:212223230188
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by:sanjay v
RegisterNumber:212223230188
'''
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:
(i) To find the L and U matrix:
![image](https://github.com/sanjayy2431/LU-Decomposition/assets/149365143/caa60f94-dc7f-4d08-94ac-32f4c7139fe1)
(ii) To find the LU Decomposition of a matrix: 
![image](https://github.com/sanjayy2431/LU-Decomposition/assets/149365143/8858ed25-e2cc-440c-b30e-50dbd0ebc4ed)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

