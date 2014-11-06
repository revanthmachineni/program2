program2
========
#include <stdio.h>


/* run this program using the console pauser or add your own getch, system("pause") or input loop */

int main()
 {
 	printf("Enter ur choice:/n1.+/n2.-/n3.*4.-");
  int r,n;
  int i,n1,n2;
 
  scanf("%d",&i);
  switch(i)
  {
  	case (1):
	  {
	   printf("Enter 2 no:");
  	   scanf("%d%d",&n1,&n2);
  	   r=n1+n2;
  	   printf("SUM=%d",r);
  		break;
  	}
  	case 2:
  		{
  		  printf("Enter 2 no:");
  	   scanf("%d%d",&n1,&n2);
  	   r=n1-n2;
  	   printf("SUB=%d",r);
  	   break;
  		}
  	case 3:
	  {
	  	printf("Enter 2 no:");
  	   scanf("%d%d",&n1,&n2);
  	   r=n1*n2;
  	   printf("MUL=%d",r);
  		break;
  	}	
  	case 4:
	  {printf("Enter 2 no:");
  	   scanf("%d%d",&n1,&n2);
  	   if(n2>=0)
		 {
		 r=n1/n2;
  	   printf("DIV=%d",r);
         }
         printf("Second no ZERO is not accepted");
  		break;
  	} 
  } 
	return 0;
}
