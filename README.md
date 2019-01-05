# Menghitung-Luas-Lingkaran
#include <iostream>
using namespace std;
int main ()
{
    int r;
    float phi=3.14, luas;
    cout<< "===== Menghitung Luas Lingkaran =====\n\n";
    cout<< " Input Jari-Jari :";
    cin>>r;
    luas=phi*r*r;
    cout<< " Luas Lingkaran :"<<luas;

    char LG;
    cout<<"\n \n\n Apakah anda ingin mengulang program ini kembali [ Y/T ] ?";cin>>LG;
if (LG=='Y' || LG=='y')main();
else if (LG=='T' || LG=='t') goto x;
x:
    return 0;
}
