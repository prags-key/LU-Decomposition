# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### (i)
### 1. import numpy as np and from scipy.linalg import lu
### 2. using np.array store matrix in variable matrix
### 3. using lu(),we can find lower triangular matrix and upper triangular matrix
### 4. print the lower triangular matrix and upper triangular matrix

### (ii)
### 1. import numpy as np and from scipy.linalg import lu_factor,lu_solve
### 2. using np.array store matrix in variable matrix
### 3. using lu_solve( ), we can find the LU decomposition of matrix
### 4. using lu_solve(), we can find the solution to linear equation Ax=b where A is matrix,x is unknown vector,b is the right hand-side vector
### 5.print the solution of vector x
## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
piv,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
Developed by: PRAGATHI KUMAR
RegisterNumber: 24006285

```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix=np.array(eval(input()))
b=np.array(eval(input()))
x=lu_factor(matrix)
sol=lu_solve(x,b)
print(sol)
Developed by: PRAGATHI KUMAR
RegisterNumber: 24006285

```

## Output:
(i)

![alt text](<L and U matrix-1.png>)

(ii)

![alt text](<LU Solve.png>)





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

