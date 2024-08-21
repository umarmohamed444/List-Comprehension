# List-Comprehension
Task 1: List Comprehension
Task:
Write a single line of code using list comprehension to generate a list of squares for the numbers 1 to 10.
Example: The output should be [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]

Python:
print([x**2 for x in range(1,11)])

Output:
[1, 4, 9, 16, 25, 36, 49, 64, 81, 100]

Screenshot:
![image](https://github.com/user-attachments/assets/5c5054e1-3835-4ef6-826d-e7753ba87293)


#Bubble Sort
Task:
Implement the Bubble Sort algorithm to sort an array of integers in ascending order.
Example: Given [64, 34, 25, 12, 22, 11, 90], the output should be [11, 12, 22, 25, 34, 64, 90].

Code:
def bubble_sort(arr):
    n=len(arr)
    for i in range(n):
        for j in range(0,n-1):
            if arr[j]>arr[j+1]:
                arr[j],arr[j+1]=arr[j+1],arr[j]
    return arr
arr=[64,34,25,12,22,11,90]
result=bubble_sort(arr)
print(result)

Output:
[11, 12, 22, 25, 34, 64, 90]

Screenshot:
![image](https://github.com/user-attachments/assets/1627e0fb-7dd9-4d8f-9d99-52bff5b067ce)

