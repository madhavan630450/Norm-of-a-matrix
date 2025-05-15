# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

# 1-Norm of a Matrix:

### STEP 1: Start the Program

### STEP 2: Import the NumPy library for matrix operations.

### STEP 3: Read the matrix from the user as a nested list (e.g., [[1,2],[3,4]]) and convert it to a NumPy array.

### STEP 4: Use np.linalg.norm(matrix, 1) which calculates the maximum absolute column sum of the matrix:

### STEP 5: Print the calculated 1-Norm of the matrix.

### STEP 6: End the program

# 2-Norm of a Matrix:

### STEP 1: Start the Program
AAA
### STEP 2: Take the matrix input from the user as a nested list (e.g., [[1, 2], [3, 4]]) and convert it into a NumPy array.

### STEP 3: Use np.linalg.norm(matrix, 2) to compute the spectral norm, which is the largest singular value of the matrix:

### STEP 4: Print the result rounded to 2 decimal places.

### STEP 5: End the program

# Infinity Norm of a Matrix:

### STEP 1:  Start the Program

### STEP 2: Import the NumPy library to perform matrix operations.

### STEP 3: Read the matrix input from the user as a nested list (e.g., [[1, -2], [3, 4]]) and convert it to a NumPy array.

### STEP 4: Use np.linalg.norm(matrix, np.inf) to calculate the ∞-norm, defined as:
            i.e., the maximum absolute row sum.

### STEP 5: Print the computed infinity norm.

### STEP 6: End the program


## Program:
Python
# Register No: 212224230153
# Developed By: MARIMUTHU MATHAVAN

# 1-Norm of a Matrix:
```
'''
Program to find 1-Norm of a matrix
Developed by:MARIMUTHU MATHAVAN
RegisterNumber:212224230153
'''
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,1)
print(result)
```

# 2-Norm of a Matrix:
```
'''
Program to find 2-norm of a matrix.
Developed by: MARIMUTHU MATHAVAN
RegisterNumber: 212224230153 
'''
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,2)
print(f"{result:.2f}")

```

# Infinity Norm of a Matrix:
```
'''
Program to find 2-norm of a matrix.
Developed by: MARIMUTHU MATHAVAN
RegisterNumber: 212224230153 
'''
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,np.inf)
print(f"{result:.2f}")

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/1f2fd6b0-48a3-481c-a9d6-db18c1f3c5b5)



### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/fbe301b0-f8f5-4e87-a7d7-0ee41feaed1a)




### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/31673137-7870-4741-99c0-81fcf9875b68)



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
