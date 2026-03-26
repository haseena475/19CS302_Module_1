# EX 3 C program to find number of years based on principle,rate & simple interest.
## DATE:17/03/2026
## AIM:
To write a C program to find number of years based on principle,rate & simple interest.

## Algorithm 
Start. Declare the variables. Prompt the user to enter a value. Read the value using scanf. Calculate the number of years using the formula: End .
## Program:
```
#include <stdio.h> 
#include <math.h>
int main()
{
float p,n,r,si,ci; 
scanf("%f%f%f", &p,&n,&r);
si=((p*n*r)/100); 
ci=(p)*(pow((1+ r/100),n));
printf("Simple Interest = %0.2f\nCompound Interest = %0.2f", si,ci);
return 0;
}
/*
Program to find number of years based on principle,rate & simple interest.
Developed by:DUDEKULA HASEENA
RegisterNumber:212222063004
*/
```

## Output:

<img width="853" height="335" alt="image" src="https://github.com/user-attachments/assets/e05eb04a-d278-4daf-9091-8e83d5d02b72" />



## Result:
Thus the program was executed and the output was verified successfully.
