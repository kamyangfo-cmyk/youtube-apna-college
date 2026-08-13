leap year 
#include <iostream>
using namespace std;
int main()
{
cout<<"check weather a year is  a leap year or not \n ";
int year;
cin>>year;
if(year%4==00)cout<<"leap year";
if(year%4!=0)cout <<"not a leap year";
return 0;
}