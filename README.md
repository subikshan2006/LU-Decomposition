# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## step-1:
Start the program.
## step-2:
End the program.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: subikshan.p
RegisterNumber:23003939
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: subikshan.p
RegisterNumber:23003939
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
*/
```

## Output:
(i) To find the L and U matrix.
![Screenshot 2023-12-28 174000](https://github.com/subikshan2006/LU-Decomposition/assets/139841805/fd2c148b-d9ed-434b-a385-8cbfd10504a6)
(ii) To find the LU Decomposition of a matrix.
![Screenshot 2023-12-28 174009](https://github.com/subikshan2006/LU-Decomposition/assets/139841805/301e1bf7-2b38-4b99-8690-f2ebe8319f4f)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

