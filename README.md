#include<stdio.h>
int main()
{
char a;
scanf("%c",&a);
if(((a>='a'&&a<='z'))||((a>='A'&&a<='Z')))
printf("the given word is an alphabet");
else
printf("the given word is not an alphabet");
}
