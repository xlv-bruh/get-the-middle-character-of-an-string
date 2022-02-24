#include <string>
using namespace std;
string get_middle(string input) 
{
  
  if(input.size() % 2 == 0){
    for(string::size_type i = 0; i < input.size(); ++i) {
      if(i == (input.size() / 2)){
        input = input[i - 1];
        input += input[i];
      }
    }
  }
  else{
    for(string::size_type i = 0; i < input.size(); ++i) {
      if(i == (input.size() / 2)){
        input = input[i];
      }
    }
  }
  return input;
 
}
