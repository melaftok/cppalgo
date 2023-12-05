This C++ code creates a program to __calculate the average__ of user input. The program continues to prompt the user for numbers until 0 is entered. The program then calculates the average of all numbers entered and displays the result.

## Code Explanation:

1. `float a, b = 0, c = 0;`  
  Declaration of variables a, b and c. b is used to count the number of data entered, and c is used for the sum of the data entered.

2. `while (a != 0)`  
  A while loop that runs until the user enters 0.

3. `b = b + 1;`  
  Increments the input counter.

4. `cout << "Data " << b << "= ";`  
  Displays a prompt for data entry.

cin >> a;: Requests input from the user and stores the entered value in the variable a.

c = c + a;: Adds the entered value to the sum of the data.

float average = c / (b - 1);: Calculates the average of the data, excluding the entered 0 from the calculation.

cout << " \n";: Adds a newline for more readable output.

cout << "Average= " << average << endl;: Displays the average value of the data.

system("pause");: Waits for a key to be pressed before closing the console window.

return 0;: Returns 0, indicating successful completion of the program.
