#include<iostream> 
using namespace std;
int main() {
	int num;
	for (int i = 0; i <= 70; i += 10)
		cout << i << " ";

	cout << endl;

	for (int i = 20; i >= -19; i--)
		cout << i << " ";

	cout << endl;

	for (int i = 3; i <= 1875; i *= 5)
		cout << i << " ";

	cout << endl;

	for (int i = 0; i < 12; i++) {
		for (int j = 0; j < 8; j++)
			cout << "*";
		cout << endl;
	}

	cout << " how many times will you like to shuffle your cards? " << endl;
	cin >> num;
	while (num != 0) {
		cout << "shuffle" << endl;
		num--;
	}
}
