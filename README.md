# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
/*
Program to find the gcd of two number using function.
Developed by: M.Krithika Lakshmi
RegisterNumber: 212224230134
*/

def gcd():
    a,b=int(input()),int(input())
    if a>b:
        small_number=b
    else:
        small_number=a
    for i in range (1,small_number+1):
        if(a%i==0 and b%i==0):
            hcf=i
    print("GCD of two numbers is:",hcf)

```

## Output:

![Screenshot 2025-05-07 153814](https://github.com/user-attachments/assets/78809ba2-b21a-488d-9654-6ee161e9220d)

## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.




## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
