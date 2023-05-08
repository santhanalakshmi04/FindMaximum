# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python
Developed by: K.SANTHANA LAKSHMI
RegisterNumber: 212222240091
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
Developed by: K.SANTHANA LAKSHMI
RegisterNumber: 212222240091
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max


```

iii) # To find the maximum marks without using builtin functions.
```Python
Developed by: K.SANTHANA LAKSHMI 
RegisterNumber: 212222240091
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i > max:
            max=i
    return max


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Screenshot (72)](https://user-images.githubusercontent.com/119475762/236777460-2d78555b-9459-4936-a5ff-04d0ed55377e.png)

![Screenshot (73)](https://user-images.githubusercontent.com/119475762/236778990-49c60821-b6e0-4644-a686-596dcf046988.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
