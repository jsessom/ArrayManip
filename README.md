# ArrayManip
Manipulating Array
#include "stdafx.h"
#include <iostream>
using namespace std;

int main()
{
	int arr[4] = { 1,2,3,4 };
	int *ptr = arr;
	cout << arr[0];

	cout << endl;
	cout<< *(++ptr);
	cout << endl;

	
    return 0;
}
