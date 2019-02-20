#include<bits/stdc++.h>
using namespace std;
int main()
{
 int t;
 cin>>t;
 for(int k=0;k<t;k++)
 {
 string s;
 int count=0;
 int m,n,r,c;
 cin>>m>>n;
 string a[m];
 for(int i=0;i<m;i++)
 cin>>a[i];
 cin>>r>>c;
 string p[r];
 for(int i=0;i<r;i++)
 cin>>p[i];
 bool flag;
 for(int i=0;i<m;i++)
 {
  flag=false;
  for(int j=0;j<n;j++)
  {
   int count=0;
   if((a[i][j]-'0')==(p[0][0]-'0'))
   {
    bool anflag=false;
    for(int e=0;e<r;e++)
    {
     for(int f=0;f<c;f++)
     {
      if(((i+e)<=(m-1))&&((j+f)<=(n-1)))
      {if((a[i+e][j+f]-'0')==(p[e][f]-'0'))
       count++;
       else
       anflag=true;
       if(count==(r*c))
       {flag=true;
       break;}}
      if(flag||anflag)
      break;
     }
     if(flag||anflag)
     break;
    }
   }
   if(flag)
   break;
  }
   if(flag)
   break;
 }
  if(flag)
  cout<<"YES"<<endl;
  else
  cout<<"NO"<<endl;
 }
 return 0;
}
