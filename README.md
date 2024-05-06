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

# Register No:212223230167
# Developed By: V RAKSHA DHARANIKA
```
```
# 1-Norm of a Matrix

import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix

![Screenshot (134)](https://github.com/rakshadharanika/Norm-of-a-matrix/assets/149348380/c0d18a73-d759-4710-8e52-64262ef1c144)

### 2-Norm of a Matrix

![Screenshot (135)](https://github.com/rakshadharanika/Norm-of-a-matrix/assets/149348380/2680a11c-b56b-45bc-afcd-95b6496bd23c)

### Infinity Norm of a Matrix

![Screenshot (136)](https://github.com/rakshadharanika/Norm-of-a-matrix/assets/149348380/0ad3d051-078b-4b0f-b7dc-e2f0e19dc6ff)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
