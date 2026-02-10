# 1st
#include <iostream>
#include <string>
using namespace std;
int main() {
    string name;
    int age;
    string major;
    float gpa;

    // Input student information
    cout << "Enter student's name: ";
    getline(cin, name);
    cout << "Enter student's age: ";
    cin >> age;
    cout << "Enter student's major: ";
    cin.ignore(); // To clear the newline character from the input buffer
    getline(std::cin, major);
    cout << "Enter student's GPA: ";
    cin >> gpa;

    // Print student information
    cout << "\nStudent Information:\n";
    cout << "Name: " << name << "\n";
    cout << "Age: " << age << "\n";
    cout << "Major: " << major << "\n";
    cout << "GPA: " << gpa << "\n";

    return 0;
}
