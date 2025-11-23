# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2. Import the necessary libraries(numpy,scipy.linalg)
3. Use lu(),lu_solve(),lu_factor() to get the solutions
4. End the program
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Kruthika R
RegisterNumber:25012308
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
Developed by: Kruthika R
RegisterNumber: 25012308
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x
*/
```

## Output:
<img width="1919" height="915" alt="Screenshot 2025-11-23 131959" src="https://github.com/user-attachments/assets/4387c8d6-a56d-4228-8444-797315ddb593" />

<img width="1917" height="864" alt="Screenshot 2025-11-23 132032" src="https://github.com/user-attachments/assets/a26bd84a-d2bb-4112-9f96-3df2bdcc19d8" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

