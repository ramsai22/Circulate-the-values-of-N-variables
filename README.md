# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
Start the program
### Step 2:
Get the inputs from the user using eval(input())
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Using concatenation operation display the entire rotated list
### Step 6: 
Stop the program
## Program:
```
#Program to circulate N values.
#Developed by: paida ramsai
#RegisterNumber: 23007931
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```

## Output:
![Screenshot 2023-11-13 131959](https://github.com/ramsai22/Circulate-the-values-of-N-variables/assets/150319855/ca550a6e-2899-4283-ac77-1a9818d5cee4)


## Result:
Thus the python program for Circulate the values of n variables is executed successfully
