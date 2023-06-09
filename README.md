# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Read the elements of augmented matrix into arrays a and b

2.Calculate elements of L and U

3.Print elements of L and U

4.Find V by solving LV = B by forward substitution

5.Find X by solving UX = V by backward substitution

6.Print Array X as the solution

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: P.V.Abishek
RegisterNumber:212222230003 
*/
import numpy as np
from scipy.linalg import lu
arr=eval(input())
P,L,U=lu(arr)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=np.array([[3,2,7],[2,3,1],[3,4,1]])
B=np.array([4,5,7])
LU,P=lu_factor(arr)
res=lu_solve((LU,P),B)
print(res)
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
*/
```

## Output:
![Screenshot 2023-06-10 000927](https://github.com/pvabishek/LU-Decomposition/assets/119405626/76d99071-b615-404e-a5c7-51684564349a)

![Screenshot 2023-06-10 000800](https://github.com/pvabishek/LU-Decomposition/assets/119405626/fc39b8c5-f496-4053-a7dc-03d0b70cc302)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

