#include <iostream> 
using namespace std; 
class Number {; 
public: 
 int num; 
 int result; 
 void res(){ 
  num = 234; 
  result = num /7; 
  cout << result; 
 } 
}; 
int main() 
{ 
 setlocale(LC_ALL, "Russian"); 
 Number num; 
 num.res(); 
  
}
