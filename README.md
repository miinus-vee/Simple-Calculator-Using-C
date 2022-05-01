# Simple-Calculator-Using-C

This program takes an arithmetic operator +, -, *, / and two operands from the user. Then, it performs the calculation on the two operands depending upon the operator entered by the user.



#include <stdio.h>

int main() {

  char op;
  double first, second;
  printf("Enter an operator (+, -, *, /): ");
  scanf("%c", &op);
  printf("Enter two operands: ");
  scanf("%lf %lf", &first, &second);

  switch (op) {
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
  }

  return 0;
}






#Output;

![image](https://user-images.githubusercontent.com/91024452/166139368-33605b22-fc40-47bd-bcf4-95acf0db5b79.png)

![image](https://user-images.githubusercontent.com/91024452/166139391-76fc3ebf-d0a5-400c-ba6d-d456ff15a8d1.png)

![image](https://user-images.githubusercontent.com/91024452/166139351-5a27a28f-f893-4ebf-b1a4-0df7a4886a1d.png)

![image](https://user-images.githubusercontent.com/91024452/166139412-dcf117ab-cb7b-4eb5-b9fd-f97b12572437.png)




