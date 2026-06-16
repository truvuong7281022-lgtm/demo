
#include <iostream>
using namespace std;

int main() {
    float dienap;
    cout << "Nhap dien ap: ";
    cin >> dienap;

    if (dienap > 220) {
        cout << "Dien ap qua tai! VUI LONG NGAT DIEN" << endl;
    }
    else if (dienap <= 200) {
        cout << "Dien ap thap! VUI LONG KIEM TRA LAI" << endl;
    }
    else {
        cout << "Dien ap binh thuong!" << endl;
    }

    return 0;
}
