# Lab-16.30-
#include <iostream>
using namespace std;

void add (int num1, int num2) {
   cout << num1 << " + " << num2 << " = "<< num1 + num2 << endl;
}
void subtract (int num1, int num2) {
  cout << num1 << " - " << num2 << " = "<< num1 - num2 << endl;
}
void multiply (int num1, int num2) {
  cout << num1 << " * " << num2 << " = "<< num1 * num2 << endl;
}
void divide (int num1, int num2) {
  cout << num1 << " / " << num2 << " = "<< num1 / num2 << endl;
}

int main() {
  double num1, num2;
  int number;
  cout << "enter two numbers\n";
  cin >> num1 >> num2;
  cout << "input 1 to add, 2 to subtract, 3 to multiply, or 4 to divide.\n";
  cin >> number;
  if (number == 1)
    add (num1, num2);
  if (number == 2)
    subtract (num1, num2);
  if (number == 3)
  multiply (num1, num2);
  if (number == 4)
  divide (num1, num2);
}
