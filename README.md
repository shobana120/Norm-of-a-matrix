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
# Register No:24007147
# Developed By:shobana b
# 1-Norm of a Matrix

	import numpy as np
	arr=np.array(eval(input()))
	result=np.linalg.norm(arr,1)
	print(result)



# 2-Norm of a Matrix

	import numpy as np
	arr=np.array(eval(input()))
	result=np.linalg.norm(arr,2)
	print("{:.2f}".format(result))



# Infinity Norm of a Matrix

	import numpy as np
	arr=np.array(eval(input()))
	result=np.linalg.norm(arr,np.inf)
	print("{:.2f}".format(result))





```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-12-08 223342](https://github.com/user-attachments/assets/10b974fd-b639-4cec-a4c0-33d7433293ce)



### 2-Norm of a Matrix
![Screenshot 2024-12-08 223329](https://github.com/user-attachments/assets/595b6a5a-e673-4eac-a04b-2cc083a6c68e)


### Infinity Norm of a Matrix
![Screenshot 2024-12-08 223310](https://github.com/user-attachments/assets/b5d5e228-5d41-423c-91ce-e3802207510d)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
