# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```
Python
# Register No: 25007890 
# Developed By: RAJESH S
# 1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
A = np.array(eval(input()))
norm = np.linalg.norm(A, 1)
print("%.2f" % norm)

# 2-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
A = np.array(eval(input()))
norm = np.linalg.norm(A, 2)
print("%.2f" % norm)

# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
A = np.array(eval(input()))
norm = np.linalg.norm(A, np.inf)
print("%.2f" % norm)

```
## Output:
### 1-Norm of a Matrix
<br>
<br> <img width="688" height="402" alt="image" src="https://github.com/user-attachments/assets/bd4ac020-d1dd-4a86-b7b0-3bc752c640ea" />
<br>

### 2-Norm of a Matrix
<br>
<br> <img width="647" height="421" alt="image" src="https://github.com/user-attachments/assets/ee9622fb-fde3-4105-9d1e-2968ad591540" />
<br>

### Infinity Norm of a Matrix
<br>
<br> <img width="677" height="392" alt="image" src="https://github.com/user-attachments/assets/7a65dc89-a3bf-4e19-b7ab-01a5d33ababe" />
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
