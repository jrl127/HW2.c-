#include <stdio.h>
#include <limits.h>

/* function declaration */
int reverseInt(int input);

int main()
{
    /** This is how your function may be tested. Actual test
     *  cases vary. There is no need to use scanf(...) for 
     *  user input. Note this main() function won't be graded.
     **/ 
     printf("%d\n", INT_MAX);
    printf("%d", INT_MIN);
    printf("%d\n", reverseInt(1234)); /* 4321 */
    printf("%d\n", reverseInt(-1)); /* -1 */
    printf("%d\n", reverseInt(-15)); /* -51 */
    printf("%d\n", reverseInt(1000000009)); /* 0, because its reverse overflows */
    /* etc */ 
    return 0;
}

/* function definition */
int reverseInt(int input) {
    
    int number, remainder, calcNumber = 0;
   
    
    while( number > 0){
    remainder = number % 10;
    number =  number / 10;
    calcNumber = (calcNumber * 10) + remainder;
    }
    
    
}
