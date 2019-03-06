# Exercicio1

#include <stdio.h>
#include <stdlib.h>

int main()
{
    system("color 0b");
    int i, n[5], quadrado;

    for (i=0; i<=4; i++)
    {
        printf("Digite um numero ");
        scanf("%d",&n[i]);
    }

    for (i=0; i<=4; i++)
    {
        quadrado=n[i]*n[i];
        printf("A raiz quadrada de %d e: %d\n",n[i],quadrado);
    }
    return 0;
}
