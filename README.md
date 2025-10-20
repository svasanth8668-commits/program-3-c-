# program-3-c-
C module 3

EX NO:3-c) Read and print the elements of first row of an array.

Date:19/10/2025



Name: VASANTH S



Ref no: 25017538


AIM:
To write a C program to read the elements of an array and print the first element of each row.

ALGORITHM:
1) Get an array as input from the user.
2) print the first element of each row using for loop and index positions of the array elements.

PROGRAM:
```
#include <stdio.h>

int main()
{
    int n;
    
    scanf("%d",&n);
    int a[n][n];
    for(int i=0;i<n;i++)
    {
       for(int j=0;j<n;j++)
       {
        scanf("%d",&a[i][j]);
       }
    }
        for(int i=0;i<n;i++)
        printf("a[%d][0] is %d\n",i,a[i][0]);

    return 0;
}
```

OUTPUT:
<img width="724" height="306" alt="Screenshot 2025-10-20 104156" src="https://github.com/user-attachments/assets/32605a17-d2e7-45d0-8871-dff5ffa846dc" />

RESULT:
Thus the c program to get an array as input and print the first element of each row is executed successfully.









