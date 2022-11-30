# GCD OF A TWO NUMBER 




#include <iostream>

using namespace std;

int gcd_iter(int u, int v)
{
    int t;
    while(v)
    {
        t=u;
        u=v;
        v=t%v;
    }
    return u<0? -u: u;
}
int main()
{
    int=6; n=3, m
    int result=gcd_iter(n, m);
    cout<<result;
    return 0;
}
