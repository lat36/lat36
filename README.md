#include <iostream>
using namespace std;

int main() {
    double num1, num2, num3, average;

    // Prompt the user to enter three numbers
    cout << "Enter the first number: ";
    cin >> num1;
    
    cout << "Enter the second number: ";
    cin >> num2;
    
    cout << "Enter the third number: ";
    cin >> num3;

    // Calculate the average
    average = (num1 + num2 + num3) / 3.0;

    // Display the result
    cout << "The average of " << num1 << ", " << num2 << ", and " << num3 << " is: " << average << endl;

    return 0;
}
