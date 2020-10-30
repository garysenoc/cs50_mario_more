#include <stdio.h>


int main(void)


{

int i,j,s,num,n;

    do
    	scanf("%d",&num);
    while(num< 1 || num>8);


    for(i=0;i<num;i++){
		for(s=0;s<num-1-i;s++)
			printf(" ");
		for(j=0;j<(num+1+i)-num;j++)
			printf("#");

printf("  ");
		for(n=0;n<(num+1+i)-num;n++)
			printf("#");
		printf("\n");

}
}
