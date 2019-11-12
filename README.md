#include<stdio.h>
int main()
{
    int choice,i;
    float price;
    for(i=1;i<=5;i++) {
        printf("[1] apples\n");
        printf("[2] pears\n");
        printf("[3]oranges\n");
        printf("[4]grapes\n");
        printf("[0]exit\n");
        printf("enter choice:");
        scanf("%d",&choice);
        if(choice==0);
        break;
        switch(choice) {
            case 1:price=3.0;break;
            case 2:price=2.5;break;
            case 3:price=4.1;break;
            case 4:price=10.2;break;
        }
        printf("price=%f\n",price);
        return 0;
    }
