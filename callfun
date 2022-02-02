#include<stdio.h>
void swap(int,int);
void main()
{
    int x,y;
    printf("Enter two numbers: ");
    scanf("%d%d",&x,&y);
    printf("Before Swapping\nx=%d\ny=%d\n",x,y);
    swap(x,y);
    return 0;
}
void swap(int a,int b)
{
    int  t;
    t =b;
    b =a;
    a =t;
    printf("After Swapping\nx=%d\ny=%d\n",a,b);
}
#include<stdio.h>
void swap(int*,int*);
main()
{
    int x,y;
    printf("Enter two numbers: ");
    scanf("%d%d",&x,&y);
    printf("Before Swapping\nx=%d\ny=%d\n",x,y);
    swap(&x,&y);
    getch();
}
void swap(int *a,int *b)
{
    int  t;
    t=*b;
    *b=*a;
    *a=t;
    printf("After Swapping\nx=%d\ny=%d\n",*a,*b);
}

