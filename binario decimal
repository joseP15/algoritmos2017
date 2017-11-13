#include "stdafx.h"
#include <iostream>
#include "math.h"
#include "conio.h"

using namespace std;

float solucion(int n);

void main(){
	
	int n, R;

	cout<< "Introduzca numero binario :" ;
	cin>> n;

	R= solucion(n);

	cout<< "Su equivalente decimal es :" << R; 

	getch();
}

float solucion(int n){
	
	int i=0, s=0, x;
	float d;

	while (n>0){
		
		d=n%10;
		s=s+(d * pow(d,i));
		n=n/10;
		i++;
	}
	return s;
}
