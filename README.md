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
# Register No:25014899
# Developed By:YUVAN RAJ R
# 1-Norm of a Matrix


import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# 2-Norm of a Matrix


import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


```
## Output:
### 1-Norm of a Matrix

<img width="592" height="227" alt="image" src="https://github.com/user-attachments/assets/e9cb6e1b-8e48-4fde-8c60-47cb46050c76" />


### 2-Norm of a Matrix

<img width="512" height="241" alt="image" src="https://github.com/user-attachments/assets/d2fbf10b-e68a-4cad-9c53-82d3c1cbc06a" />


### Infinity Norm of a Matrix

<img width="568" height="202" alt="image" src="https://github.com/user-attachments/assets/8b3230b1-851a-4541-a63c-225fdfa98159" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
