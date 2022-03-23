#include"stdio.h"
main()
{
    char a[100]="chinese in china is very good";
    char b[]="in";
    int i,j=0,sum=0;
    for(i=0;a[i]!='\0';i++)
        if(a[i]==b[j])
            if(a[i+1]==b[j+1])
                sum++;
			printf("%d",sum);

}
