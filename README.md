<center><h3>C</h3></center>
<hr />

C programming libraries, tutorials, and guides.

These programs are meant to help others get started quicker 
on their own projects and also help them understand certain 
coding techniques and ideas.

Do with them what you want and feel free to send updates or 
improvements or ideas.
double firstNumber, secondNumber, temporaryVariable;
      printf("Enter first number: ");
      scanf("%lf", &firstNumber);
      printf("Enter second number: ");
      scanf("%lf",&secondNumber);
    
      temporaryVariable = firstNumber;
    
      firstNumber = secondNumber;
      
      secondNumber = temporaryVariable;
      printf("\nAfter swapping, firstNumber = %.2lf\n", firstNumber);
      printf("After swapping, secondNumber = %.2lf", secondNumber);
