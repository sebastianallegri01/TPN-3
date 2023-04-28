#include <bits/stdc++.h>

using namespace std;

int EstMayor(int n1 ,int n2 ,int n3);

int main(){
	int n1,n2,n3;
	
	cout<<"Ingrese tres numeros: "<<endl;
	cin>>n1>>n2>>n3;
	
	cout<<"El numero mas grande que ingreso es el: "<<EstMayor(n1,n2,n3);
	
	return 0;
	}

int EstMayor(int n1 ,int n2 ,int n3){
	int mayor;
	if(n1<n2 && n1<n3){
		mayor=n1;
	}
		if(n2<n1 && n2<n3){
		mayor=n2;
	}
		if(n3<n2 && n3<n1){
		mayor=n3;
	}
}
