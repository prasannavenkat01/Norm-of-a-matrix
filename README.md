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
# Register No:23006873
# Developed By:PRASANNA V
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
nom = "{:.2f}".format(ans)
print(nom)



# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
nom ="{:.2f}".format(ans)
print(nom)



# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
nom ="{:.2f}".format(ans)
print(nom)




```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-25 133708](https://github.com/prasannavenkat01/Norm-of-a-matrix/assets/150702500/f59650b1-e899-497b-a76b-8e25d5d99154)

### 2-Norm of a Matrix
![Screenshot 2023-12-25 133733](https://github.com/prasannavenkat01/Norm-of-a-matrix/assets/150702500/9455b05d-9d9e-4041-9510-ab68e2fa63fd)


### Infinity Norm of a Matrix
![Screenshot 2023-12-25 133750](https://github.com/prasannavenkat01/Norm-of-a-matrix/assets/150702500/77da73f7-6446-463d-b0d9-f3ae8b7e5a86)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
