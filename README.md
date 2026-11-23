# computer-science-lab
Computer Science practical programs, notes and lab manuals
#include <stdio.h>

int main()
{
float celsius, fahrenheit;

printf("Enter temperature in Celsius: ");
scanf("%f", &celsius);

fahrenheit = (celsius * 9 / 5) + 32;
printf("Celsius to Fahrenheit = %.2f\n", fahrenheit);

printf("Enter temperature in Fahrenheit: ");
scanf("%f", &fahrenheit);

celsius = (fahrenheit - 32) * 5 / 9;
printf("Fahrenheit to Celsius = %.2f\n", celsius);

return 0;

}
