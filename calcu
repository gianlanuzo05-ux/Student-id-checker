#include <iostream>
#include <vector>
#include <string>
#include <algorithm>
using namespace std;

int main () {
	int choice;
	string StudentPIN;
	int num1, num2;
	char operation;
	
	vector<string> validIDs = {
	      "",
	      "",
	      ""
	};
	
	cout << "Enter your PIN: ";
	getline (cin, StudentPIN);
	
	bool isValid = find(validIDs.begin(), validIDs.end(), StudentPIN) != validIDs.end();
	if(isValid) {
		cout << "\nCorrect PIN, Proccess to Portal\n";
		
		
		do {
			cout << "\nChoose operation you want:\n";
			cout << "1. Addition(+)\n";
			cout << "2. Subtraction(-)\n";
			cout << "3. Multiplication(*)\n";
			cout << "4. Division(/)\n";
			cout << "5. Exit\n";
			cout << "Enter your choice: ";
			cin >> choice;
			
			switch(choice) {
				case 1:
					cout << "Enter fist number: ";
					cin >> num1;
					
					cout << "Enter operation(+): ";
					cin >> operation;
					
					cout << "Enter second number: ";
					cin >> num2;
					
					if(operation == '+') {
						cout << num1 + num2;
					} else {
						cout << "Invalid operation!";
					}
					break;
					
					case 2:
						cout << "Enter fist number: ";
					cin >> num1;
					
					cout << "Enter operation(-): ";
					cin >> operation;
					
					cout << "Enter second number: ";
					cin >> num2;
					
					if(operation == '-') {
						cout << num1 - num2;
					} else {
						cout << "Invalid operation!";
					}
					break;
					
					case 3:
					    cout << "Enter fist number: ";
					cin >> num1;
					
					cout << "Enter operation(*): ";
					cin >> operation;
					
					cout << "Enter second number: ";
					cin >> num2;
					
					if(operation == '*') {
						cout << num1 * num2;
					} else {
						cout << "Invalid operation!";
					}
					break;
					
					case 4:
					     cout << "Enter fist number: ";
					cin >> num1;
					
					cout << "Enter operation(/): ";
					cin >> operation;
					
					cout << "Enter second number: ";
					cin >> num2;
					
					if(num2 != 0) {
						cout << num1 / num2;
					} else {
						cout << "Cannot divide by zero!";
					}
					break;
					
					case 5:
					     cout << "Thank you!";
						 break;
						 
						 default:
						 cout << "Invalid Choice!"; 
			}
		} while(choice != 5);
	} else {
		cout << "Invalid PIN!";
	}
	return 0;
}
