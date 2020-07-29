# a
#include <iostream>
using namespace std;
void main()
{
	int a[10],i=0,j,t;
	cout<<"排序前:"<<endl;
	for(i=0;i<10;i++)
		cin>>a[i];
	cout<<endl;
	for(i=0;i<10;i++)
		for(j=0;j<9;j++)
			if(a[j]>a[j+1])
			{
				t=a[j];
				a[j]=a[j+1];
				a[j+1]=t;
			}
			cout<<"排序后"<<endl;
			for(i=0;i<10;i++)
			cout<<a[i]<<" ";
			cout<<endl;
}
