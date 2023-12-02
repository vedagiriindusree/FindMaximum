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
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Vedagiri Indu sree
RegisterNumber: 23004520
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

ii)	# To find the maximum marks using the list method max().
''' 
Program to find the maximum marks using the list method max().
Developed by: Vedagiri Indu Sree
RegisterNumber: 23004520
'''
def max_marks(marks):
    marks.sort()
    res=marks[-1]
    return res

iii) # To find the maximum marks without using builtin functions.
''' 
Program to the maximum marks without using builtin functions.
Developed by: Vedagiri Indu sree
RegisterNumber: 23004520
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
## Sample Input and Output
![image](https://github.com/vedagiriindusree/FindMaximum/assets/149366776/93ce8a18-17a7-4295-bbb9-4b0b2754c203)
![image](https://github.com/vedagiriindusree/FindMaximum/assets/149366776/1c2248fd-1658-4ff9-923f-ecdecd9058fb)
![image](https://github.com/vedagiriindusree/FindMaximum/assets/149366776/5c8440cc-ec6c-4c6f-95a3-0163280ac58f)
## Output:
![image](https://github.com/vedagiriindusree/FindMaximum/assets/149366776/8ac33eef-93e7-4b79-9be1-3cd0cae29821)
![image](https://github.com/vedagiriindusree/FindMaximum/assets/149366776/e726ee5e-ce37-4f81-8ba3-eaa9dcd46ad2)
![image](https://github.com/vedagiriindusree/FindMaximum/assets/149366776/849fec17-bcba-4a8c-b704-88d604ea9e0e)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
