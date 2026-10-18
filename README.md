# multiplication-of-two-array-


#include <iostream>
using namespace std;

int main()
{
    int a[5], b[5], mul[5];
    int i, choice;

    cout << "Enter 5 elements of first array:\n";
    for (i = 0; i < 5; i++)
    {
        cin >> a[i];
    }

    cout << "Enter 5 elements of second array:\n";
    for (i = 0; i < 5; i++)
    {
        cin >> b[i];
    }

    cout << "\n1. Multiply two arrays";
    cout << "\nEnter your choice: ";
    cin >> choice;

    switch (choice)
    {
        case 1:
            for (i = 0; i < 5; i++)
            {
                mul[i] = a[i] * b[i];
            }

            cout << "Multiplication of two arrays:\n";
            for (i = 0; i < 5; i++)
            {
                cout << mul[i] << " ";
            }
            break;

        default:
            cout << "Invalid choice";
    }

    return 0;
}
