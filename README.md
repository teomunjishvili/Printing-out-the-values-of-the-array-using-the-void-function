#include<iostream>
using namespace std;

void Array(int a[5])
{
    for(int i=0; i<5; i++)
        cout<<a[i]<<endl;
}

int main()
{
    int a[5]={100,200,300,400,500};
    Array(a);
    
    return 0;
}
