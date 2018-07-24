#include<iostream.h>
#include<conio.h>
voidmain()
{
int x;
clrscr();
cout<<"enter the year";
cin>>x;
if(x%4==0)
{
cout<<"it is leap year"<<x;
}
else
{
cout<<"it is not a leap year"<<x;
}
getch();
}
