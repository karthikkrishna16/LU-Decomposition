# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X' 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: TH KARTHIK KRISNA
RegisterNumber: 23014165
#To print L and U matrix
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: TH KARTHIK KRISHNA
RegisterNumber: 23014165
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
*/
```

## Output:
![Screenshot 2023-12-28 194730](https://github.com/karthikkrishna16/LU-Decomposition/assets/148514663/5eb38b47-b83c-40cd-b12f-6d3682974e11)


![Screenshot 2023-12-28 194747](https://github.com/karthikkrishna16/LU-Decomposition/assets/148514663/39dfeb49-364b-4b34-8898-df2a47551cd0)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

