# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
DIFINE THE CIRCULATE FUNCTION
### Step 2:
ACCEPT S LIST FROM THE USER AND EVALUATE IT USING EVAL
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
GIVE PRINT STATEMENT TO PRINT THE LIST
### Step 6: 
CALL THE CIRCULATE FUNCTION
## Program:
#program to circulate n variable
#developed by:naresh.r
#Registernumber:23005559
def circulate():
  l=eval(input())
  n=int(input())
  l=l[n:]+l[:n]
  print("After circulating the values are:",l)

## Output:
![Screenshot 2023-11-14 112204](https://github.com/feryjfgkuyfgewjfgew/Circulate-the-values-of-N-variables/assets/150319377/dfa481c0-042b-41ab-9270-7051b5a088df)


## Result:
thus the circulating n variables executed successfully
