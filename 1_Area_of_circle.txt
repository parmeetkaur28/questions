#include<stdio.h>
#include<conio.h>

void main()
{
    float r, area;
    clrscr();
    printf("Enter the radius of the circle: ");
    scanf("%f",&r);
    area=3.14*r*r;
    printf("\nThe area of the circle is %f",area);
    getch();
}