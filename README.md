#include<stdio.h>

int main()
{
	double sum = 0;
	int jc = 1, n;
	scanf("%d",&n);
	for(int i = 1;i <= n;i++) 
	{
		jc *= i;
		sum += 1.0/jc;
	}
	printf("%.12lf",sum+1);
	return 0;
 } 
