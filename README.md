# longest-Consecutive-1S

#include<bits/stdc++.h>
using namespace std;

class Aditya
{
    public:
    int maxConsecutiveOnes(int N)
{
  int x,count=0;  
while(x!=0)
{
x = x&(x>>1);
count++;
}
return count; 
}
};

int main()
{
int t;
cin >> t;
while(t--)
{
int K.N;
cin >> K >> N;
Aditya ob;
int ans = ob.setKthBit(int N, int K);
cout << ans << end;
}
return 0;
