## Date:
# Ex-2 : Circulate-the-values-of-N-variables

## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the values from the user
### Step 2: 
Assign the value of variable to a temporary variable
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Print both the values it would be interchanged
### Step 6: 
End the program
## Program:
```
# Developed by:Mohamed Rashith s
# Register no:24001082
def circulate():
    global lst,n
    n = n % len(lst)
    rotated_list = lst[n:] + lst[:n]
    print(f"After circulating the values are: {rotated_list}")
lst=list(eval(input()))
n = int(input())
```

## Output:

![py 2](https://github.com/user-attachments/assets/c5d1c19d-4272-4a94-95fa-cdd36afdf722)


## Result:
The output for circulate the values of n variables is successfull.

