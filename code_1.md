#include<stdio.h>
int main()

{

    char o;
    
    double first, second;
    
    printf("Enter an operator (+, -, *,/)");
    
    scanf("%c", &o);
    
    printf("Enter two operands: ");
    
    scanf("%lf %lf", &first, &second);
    
    switch (o) 
    {
    case '+':
        printf("%.1lf + %.1lf = %.1lf", first, second, first + second);
        break;
    case '-':
        printf("%.1lf - %.1lf = %.1lf", first, second, first - second);
        break;
    case '*':
        printf("%.1lf * %.1lf = %.1lf", first, second, first * second);
        break;
    case '/':
        printf("%.1lf / %.1lf = %.1lf", first, second, first / second);
        break;
        // operator doesn't match any case constant
    default:
        printf("Error! operator is not correct");
	printf("Error! operator is not correct");
	//Somechanges has to be done
    }

    return 0;
}
