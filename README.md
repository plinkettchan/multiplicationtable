
# include <stdio.h>
# include <cs50.h>



void multiplication_table(int n)
{
    printf("Multiplication table of 1\n");
    for (int i = 1; i < 11; i++)
    {
        printf("%d\n", i);
    }
    printf("Multiplication table of 2\n");
      
      
    for (int i = 1; i < 11; i++)
    {
        printf("%d\n", i * 2);
    }
    printf("Multiplication table of 3\n");
      
      
    for (int i = 1; i < 11; i++)
    {
        printf("%d\n", i * 3);
    }

    
}

int main(void)
{
    multiplication_table(1);
   

}


