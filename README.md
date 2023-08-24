# Simple-Interest
#include<iostream>
using namespace std;

int main()
{
    float p,r,t,si;
    cout<<"Enter the principle :- ";
    cin>>p;
    cout<<"Enter the rate :-";
    cin>>r;
    cout<<"Enter the time :-";
    cin>>t;
    si=(p*r*t)/100;
    cout<<"Simple interest= "<< si <<endl;
    return 0;
}

