#include<stdio.h>
#include<conio.h>
void main()
{
int a=5,b=3,c,*p,*q,*r;
p=&a;
q=&b;
r=&c;
clrscr();
*r=*p+*q;
printf("%d",*r);
getch();
}
