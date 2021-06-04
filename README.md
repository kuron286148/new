# new

#include<stdio.h>

int main(void){
    char str[10000];
    int a=0;
    int b=0;
    printf("文字列を入力してください.\n");
    scanf("%s",str);
    for(a=0;str[a]!='\0';a++){
    b++;}
    for(a=b-1;a>=0;a--){
    printf("%c",str[a]);
    }
    printf("\n");
    return 0;
}
