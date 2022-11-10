//# maximum-number.c//
#include<stdio.h>
int main()
{
    int num1,num2;
    printf("enter first number");
    scanf("%d",&num1);
    printf("enter seconf number");
    scanf("%d",&num2);
    if(num1>num2)
    {
        printf("num1 is maximum number\n");
    }
    else
    {
        printf("num1 is minimum number\n");
    }
    return 0;
}
