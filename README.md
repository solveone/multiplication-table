# multiplication-table
#include<stdio.h>
int main (void)
{
	int i,h;
	int shu[9]={1,2,3,4,5,6,7,8,9};
 	h=0;
	while(h<9)
	{
		for(i=0;i<h+1;i++)
			printf("%dx%d=%-5d",shu[i],shu[h],shu[i]*shu[h]);
		h++;	
		printf("\n");
	}
	return 0;
}
