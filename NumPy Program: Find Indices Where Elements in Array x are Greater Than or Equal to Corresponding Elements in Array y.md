# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program

Add code here
~~~
import numpy as np

arr = np.array([[1, 2, 3],
                [4, 5, 6],
                [7, 8, 9]])

new_col = np.array([10, 11, 12])

arr = np.delete(arr, 1, axis=1)
arr = np.insert(arr, 1, new_col, axis=1)

print("Updated Array:")
print(arr)
~~~

## Output
<img width="1569" height="997" alt="530370747-4d35f1dc-8a64-4266-ac95-0404eb996143" src="https://github.com/user-attachments/assets/52bf0550-67ce-4aad-8f01-39f892197d96" />

## Result
The NumPy program successfully deletes the second column from a given 2D array and inserts a new column at the same position.
