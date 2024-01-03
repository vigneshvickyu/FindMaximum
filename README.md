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
''' 
Program to mark the maximum of marks using the list method sort
Developed by:VIGNESH M 
RegisterNumber: 23014020
'''
def max_marks(marks):
    marks.sort()
    return marks[-1]
    #Write your code here
''' 
Program to find the maximum marks using the list method max().
Developed by: VIGNESH M
RegisterNumber:23014020 
'''
def max_marks(marks):
    return max(marks)
    # write your code here
''' 
Program to the maximum marks without using builtin functions.
Developed by: VIGNESH M
RegisterNumber: 23014020
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
    # write your code here


## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![image](https://github.com/vigneshvickyu/FindMaximum/assets/151948835/f1f75233-6dcb-4545-af6e-b594d55dff87)
![image](https://github.com/vigneshvickyu/FindMaximum/assets/151948835/7e97ed7e-dbb8-4b8d-a977-b13e3b5376f3)
![image](https://github.com/vigneshvickyu/FindMaximum/assets/151948835/eeb906b1-6ceb-4cbd-9f1d-3e7bbb07e048)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
