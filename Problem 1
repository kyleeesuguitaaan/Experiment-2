#include <iostream>
#include <conio.h>

using namespace std;

int main ()
{
	// Variables
	int A1, B1, C;
	char Packages;
	double hours, a1, b2;
	
	A1 = 995;
	B1 = 1495;
	C = 1995;
	
	// Packages
	cout << "\t\t Menu of Subscription Packages \n\n";
	cout << "Package [a]: Php 995 per month 10 hours of access. For additional hours it costs Php 20 per hour. \n";
	cout << "Package [b]: Php 1495 per month 20 hours of access. For additional hours it costs Php 10 per hour. \n";
	cout << "Package [c]: Php 1995 per month of unlimted access.\n";
	
	cout << "\n\nWhat Subscription Package do you wish dear client? \n";
	cout << "Packages ";
	cin >> Packages;
	cout << "\n";
	
	switch (Packages)
	{
		case 'A':
		case 'a':
			cout << "Thank you for chosen Subscription A. \n\n";
			cout << "how many hours you execeeded in this package? \n ";
			cin >> hours;
			
			if (hours <= 10){
				
				cout << "\nThat price would be " << A1;
				cout << "\nThank you and God bless!";
			}else{
			A1 = (hours -10)*20 +995;
			cout << "\nThat price would be " << A1;
			cout << "\nThank you and God bless!";
			}
			break;
			
			case 'B':
			case 'b':
				cout << "Thank you for chosen Subscription B. \n\n";
				cout << "how many hours you execeeded in this package? \n ";
				cin >> hours;
				
				if (hours <= 20) {
					B1 = (hours -20)*10 +1495;
					cout << "\nThat price would be "<< B1;
					cout << "\n Thank you and God bless!";
				}else {
				B1 =(hours -20)*10 +1495;
				cout << "\nThat price would be" << B1;
				cout << "\nThank you and God bless!";
				}
				break;
			
			case 'C':
			case 'c':
				cout << "Thank you for chosen Subscription C. \n\n";
				cout << "\nThat will cost you Php 1995 \n";
				cout << "Thank you and God bless!";
			
			default:
				cout << "Please enter A - C only \n";				
    	}
    	_getch();
    	return 0;
}
