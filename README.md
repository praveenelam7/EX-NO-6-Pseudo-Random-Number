# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>
                        
int main()
{
    int i;

    srand(time(0));

    printf("Pseudo-Random Numbers:\n");

    for (i = 0; i < 5; i++)
        printf("%d\n", rand() % 100);

    return 0;
}
```

# OUTPUT:
<img width="1457" height="592" alt="image" src="https://github.com/user-attachments/assets/bff24760-ec2c-4d54-8144-4cf5df196a33" />

# RESULT:
