/// Accept-number-from-user-and-Find-its-square

#include<stdio.h>
 square(num)
{
  return (num * num);
}
int main()
{
int num,n;
printf("\n===========xoxoxoxox============\n");
printf("\nInput any number for square :");
scanf("%d",&num);
n = square(num);
printf("\nThe square of %d is : %d\n",num,n);
printf("\n\n===========xoxoxoxox============");
getch();
return 0;
}
