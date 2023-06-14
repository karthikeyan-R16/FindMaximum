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
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Karthikeyan R
RegisterNumber: 212222240045
'''
def max_marks(marks):
    marks.sort()
    return marks[-1]



```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Karthikeyan R
RegisterNumber: 212222240045
'''
def max_marks(marks):
    return max(marks)
```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Karthikeyan R
RegisterNumber: 212222240045
'''
def max_marks(list1):
    l=list1[0]
    for i in list1:
        if i>l:
            l=i
    return l        

```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
i) # To find the maximum of marks using the list method sort.

![image](https://github.com/karthikeyan-R16/FindMaximum/assets/119421232/dd676b70-5835-4f9a-be13-7fc8e7c520fe)

ii) # To find the maximum marks using the list method max().

![image](https://github.com/karthikeyan-R16/FindMaximum/assets/119421232/d1015b09-ada3-4d5a-9662-6809c22b247c)

iii) # To find the maximum marks without using builtin functions.

![image](https://github.com/karthikeyan-R16/FindMaximum/assets/119421232/7a255daa-3829-4199-a378-9e49876bedce)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
