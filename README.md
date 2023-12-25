# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy library as np
2. create a matrix using np.array()
3. using scipy.linalg.lu() find L and U,also using scipy.linalg.li_solve() get the result for LU decomposition
4. get the output and end the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Nirosha M
RegisterNumber: 23014438
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Nirosha M
RegisterNumber: 23014438
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
*/
```

## Output:
![Screenshot 2023-12-12 185037](https://github.com/niroshamuthukumar/LU-Decomposition/assets/151830921/ceb69ec5-8a66-4887-adce-63b42f2b2d83)
![Screenshot 2023-12-12 185530](https://github.com/niroshamuthukumar/LU-Decomposition/assets/151830921/c446a949-de18-4ff1-909e-91e0587e66f8)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

