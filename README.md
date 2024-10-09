#include <iostream>
using namespace std;

int main() {
    // Змінні для введення c і d
    double c, d;

    // Введення значень з клавіатури
    cout << "Введіть значення c: ";
    cin >> c;
    cout << "Введіть значення d: ";
    cin >> d;

    // Обчислення виразу c + 4d
    double result = c + 4 * d;

    // Виведення результату
    cout << "Результат: " << result << endl;

    return 0;
}

