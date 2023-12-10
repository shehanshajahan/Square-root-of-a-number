# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```
Program to find the square root for the given number(newton's method) using function.
Developed by: Shehan Shajahan      
RegisterNumber:  23008724

b=int(input())
x=0.5*b
root=0.5*(x+b/x)
while root!=x:
    x=root
    root=0.5*(x+b/x)
print("Square root of the number:",root)

```

## Output:
![image](https://github.com/shehanshajahan/Square-root-of-a-number/assets/139317389/23f6441b-48d7-43da-9809-6390f025077e)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
