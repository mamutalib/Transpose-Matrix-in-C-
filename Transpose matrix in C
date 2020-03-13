/* Transpose matrix in C */
#include <stdio.h>
int main()
{
    int mat[15][15],row,col,i,j,tp[10][10];
    printf("Enter row and coloum: ");
    scanf("%d%d",&row,&col); //taking row & coloum
    printf("Enter the element of the matrix: ");
    for(i=0;i<row;i++)
    {
        for(j=0;j<col;j++)
        {
            scanf("%d",&mat[i][j]);
        }
    }
    printf("The matirx is: \n");
    for(i=0;i<row;i++)
    {
        printf("\t");
        for(j=0;j<col;j++)
        {
            printf("%d ",mat[i][j]);
        }
        printf("\n");
    }
    
    for(i=0;i<row;i++)
    {
        for(j=0;j<col;j++)
        {
            tp[j][i]=mat[i][j];
        }
    }
    printf("The transpose mattix is: \n");
    for(i=0;i<col;i++)
    {
        printf("\t");
        for(j=0;j<row;j++)
        {
            printf("%d ",tp[i][j]);
        }
        printf("\n");
    }
    return 0;
}
