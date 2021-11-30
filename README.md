# cplus2.0_double_averagegrade.
average grade.

#include <iostream>
using namespace std;
int main ()
{
    int num;
    double num1, num2, num3, num4, num5;
    int average;

    cout << "Salazar, Iren Mercado" << endl;
    
    
    cout << " Enter a number: " << endl;
    cin >> num1;
    
    cout << "Enter a number: " << endl;
    cin >> num2;
   
    cout << "Enter a number: " << endl;
    cin >> num3;
    
    cout << "Enter a number: " << endl;
    cin >> num4;
  
    cout << "Enter a number: " << endl;
    cin >> num5;
   
    average = (num1+num2+num3+num4+num5) /5;
    
    cout << average<< " Is the average grade." << endl;
    return 0;
}
  /*output:
  
  Salazar, Iren Mercado
  Enter a number: 
  12
  Enter a number: 
  12
  Enter a number: 
  12
  Enter a number: 
  67
  Enter a number: 
  54
  31 Is the average grade */
  
