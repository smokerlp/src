src
===

soucer#include <stdlib.h>
#include <stdio.h>

int main(){

int altura, media=0, alto=0, baixo, cont=0, x=1;

baixo=altura;
while(x==1){
    scanf("%d", &altura);
    if(baixo>altura)
        baixo=altura;
    if(alto<altura)
        alto=altura;
    media+=altura;
    cont++;
    scanf("%d",&x);
 }
media/=cont;
printf("alto %d \t baixo %d \t media %d \t", alto, baixo, media);

return 0;
}
