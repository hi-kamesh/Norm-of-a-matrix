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
```Python
# Register No:2406248
# Developed By:kamesh
# 1-Norm of a Matrix
import numpy as np 

mat=np.array(eval(input()))

ans=np.linalg.norm(mat,1)

norm_of_matrix="{:.2f}".format(ans)

print(norm_of_matrix)



# 2-Norm of a Matrix
import numpy as np 

mat=np.array(eval(input()))

ans=np.linalg.norm(mat,2)

norm_of_matrix="{:.2f}".format(ans)

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
![Screenshot 2024-12-03 102622](https://github.com/user-attachments/assets/73376ad9-806e-4bf6-936d-65d51a929b41)


### 2-Norm of a Matrix
![Screenshot 2024-12-03 102630](https://github.com/user-attachments/assets/a30f2c9e-3241-445a-b1cb-59a575c0b538)


### Infinity Norm of a Matrix
![Screenshot 2024-12-03 102641](https://github.com/user-attachments/assets/f69bbf13-c96a-45ee-b10e-dd6b00073ae6)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
