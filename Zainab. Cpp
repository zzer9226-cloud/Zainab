#include <iostream>
using namespace std;

int main()
{
    int consumption;        // كمية الاستهلاك
    int pricePerUnit;       // سعر الوحدة
    int totalBill;          // المبلغ الكلي

    // طلب إدخال الاستهلاك
    cout << "Enter electricity consumption (in kilowatts): ";
    cin >> consumption;

    // تحديد سعر الوحدة حسب الاستهلاك
    if (consumption <= 100)
    {
        pricePerUnit = 250;
    }
    else if (consumption <= 300)
    {
        pricePerUnit = 300;
    }
    else
    {
        pricePerUnit = 350;
    }

    // حساب المبلغ الكلي
    totalBill = consumption * pricePerUnit;

    // تقييم الاستهلاك
    if (totalBill > 100000)
    {
        cout << "\nHigh consumption – Please reduce usage\n";
    }
    else
    {
        cout << "\nNormal consumption\n";
    }

    // عرض النتائج
    cout << "\nElectricity consumption: " << consumption << " units" << endl;
    cout << "Price per unit: " << pricePerUnit << " IQD" << endl;
    cout << "Total bill amount: " << totalBill << " IQD" << endl;

    return 0;
}
