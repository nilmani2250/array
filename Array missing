#include<stdio.h>
void main()
{
  int n,i,c,start,end,nomissing=0;
  printf("Enter the number element\n");
  scanf("%d",&n);
  int a[n];
  printf("Enter %d array\n",n);
  for(i=0;i<n;i++)
  {
     scanf("%d",&a[i]);
  }
  printf("Enter the start and end value\n");
  scanf("%d %d",&start,&end);
  printf("Missing array number range of %d to %d\n",start,end);

  while(start<=end)
  {
    c=0;
    for(i=0;i<n;i++)
    {
      if(start==a[i])
      {
        c=1;
        break;
      }
    }
    if(c==0)
    {
      printf("%d ",start);
      nomissing=1;
    }
    start++;
    }
    if(nomissing==0)
    printf("There is no missing array\n");
}
