Project Title: Simple Calculator with Unit Testing
Student Name: Suhier Fath alrahman Omer 
Instructor: Dr.Suhier Fath alrahman Omer 
Programming Language: Java 

Description:
This project implements a simple calculator using Java .
It supports addition


#include <iostream>
using namespace std;

int main() {
    // مدخلات تجريبية للاختبار
    int test_a = 10;
    int test_b = 20;
    int expected_result = 30; // النتيجة المتوقعة

    // تنفيذ عملية الجمع
    int actual_result = test_a + test_b;

    // اختبار البرنامج لنفسه
    cout << "Testing 10 + 20..." << endl;

    if (actual_result == expected_result) {
        cout << "Test Passed! Result is: " << actual_result << endl;
    } else {
        cout << "Test Failed! Something is wrong." << endl;;
    }

    return 0;
}
