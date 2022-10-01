# Printing-Star-Patterns

#include <stdio.h>
int main()
{
    int input, n;
    char star = '*';
    printf("Enter 0 for triangular star pattern\nEnter 1 for Reversed Triangular star pattern \t");
    scanf("%d", &input);

    printf("Enter the no. of rows: ");
    scanf("%d", &n);

    if (input == 0)
    {
        printf("Printing triangular star pattern\n");
        for (int i = 0; i < n; i++)
        {
            for (int j = 0; j <= i; j++)
            {
                printf("*");
            }
            printf("\n");
        }
    }
    else
    {
        printf("Wrong input");
    }

    return 0;
}
