#include<studio.h>
int main()
{
  int i,j;
  for(i=1;i<=6;i++)
   { 
      for(j=1;j<=i*2;j++)
        {
          if(j%2==0)
             printf("1");
          else
             printf("0");
        }
       printf("\n");
    }
 return 0;
}
