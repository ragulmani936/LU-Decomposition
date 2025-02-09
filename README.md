# LU Decomposition without zero on the diagonal

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1:
Import numpy library using import statement.

### Step 2:
From scipy package import lu().

### Step 3:
Get input from user and pass it as an array.

### Step 4:
Get P, L, U matrix using lu()

### Step 5:
Print L and U matrix

## Program:
```
Program to find the LU Decomposition of a matrix.
Developed by:Ragul.M 
RegisterNumber: 21500303
```
~~~
import numpy as np
from scipy. linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
~~~
```
Program to solve a matrix using LU decomposition.
Developed by:Ragul.M 
RegisterNumber: 21500303
```
~~~
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
~~~



## Output:
Program to find the LU Decomposition of a matrix.
![lu decomposition](https://github.com/ragulmani936/LU-Decomposition/blob/main/Screenshot%20(29).png?raw=true)     Program to solve a matrix using LU decomposition.
![lu decomposition](https://github.com/ragulmani936/LU-Decomposition/blob/main/Screenshot%20(30).png?raw=true)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

