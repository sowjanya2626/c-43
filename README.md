# c-43
Double pointers
#include<stdio.h>
int main()
{
   int a=1000;
   int *ptr = &a;
   int **pptr = &ptr;
   printf("given value:%d\n",a);
   printf("single ptr value:%d\n",*ptr);
   printf("double ptr value:%d\n",**pptr);
    return 0;
}
