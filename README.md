# xor_code_shef
#First practice problem on code shef

#include <stdio.h>

int main(void)
{
   int num[5],n,totalxor=0 ,i ;
   printf("enter no of elements");
   scanf("%d",&n);
  
  printf("enter numbers");
  for(i=0 ; i < n ; i++ ) 
  {
    scanf("%d",&num[i]);  
}
  for(i=0 ; i<n ; i++ )
  {
     totalxor = totalxor ^ num[i] ;
  } 
 
 if(totalxor %2 ==0) 
{  
    printf("\neven") ; 
}     
 else
    printf ("\nodd") ; 
   
	return 0;
