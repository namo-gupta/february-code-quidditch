#include<iostream>
using namespace std;
int main()
{
    int m,n,i,temp=0;
    char op[100000];
    cin>>m>>n;
    cin>>op;
    for(i=0;i<m;i++)
    {
        if(temp==n)
            break;
        if(op[0]!='1')
        {
            op[0]='1';
            temp++;
            continue;
        }
        if(op[i]!='0')
        {
            op[i]='0';
            temp++;
        }
    }
    cout<<op;
    return 0;
}
