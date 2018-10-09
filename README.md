# praktikum1
## Latihan1.cpp program .....

Penjelasan

1. Deklarasi variabel int panjang, lebar, luas sebagai variabel input
2. Masukan input ke dalam variabel
3. Tunjukan hasil perkalian dari kedua variabel

```
#include<iostream>
using namespace std;

    int main (){

        int panjang,lebar,luas;

        panjang=5;
        lebar=5;

        luas=panjang * lebar;

        cout << "panjang: " << panjang << endl;
        cout << "lebar: " << lebar;
        cout << endl;
        cout << "rumus mencari luas: " << panjang << " x " << lebar;
        cout << endl;
        cout << "luas: " << luas;
        cout << endl;

    }
```

## Latihan2.cpp program

Penjelasan

1. Masukan bilangan ke variabel a
2. Bagi bilangan dengan bilangan 2
3. Jika hasil 0 maka bilangan genap
4. Jika tidak hasilnya ganjil 
5. Tampilkan variabel hasil

```
#include<iostream>
using namespace std;

int main(){

    int angka,hasil;

    cout<< "masukan bilangan: ";
    cin>> angka;
    cout << endl;

    hasil=angka % 2;

    if(hasil == 0){

        cout<< angka << " sama dengan bilangan genap" << endl;

    }else{

        cout<< angka << " sama dengan bilangan ganjil" << endl;
    }
```

## latihan3.cpp program

Penjelasan

1. Masukan angka1, angka2, besar, kecil
2. Masukan angka1
3. Masukan angka2
4. Apakah angka1 lebih besar dari pada angka2. jika iya maka angka1 akan lebih besar dari angka2 dan sebaliknya
5. Apakah angka1 lebih kecil dari pada angka2. jika iya maka angka1 akan lebih keci dari angka2 dan sebaliknya


#include<iostream>
using namespace std;

int main(){

    int angka1,angka2,besar,kecil;

    cout << "masukan angka ke-1: ";
    cin >> angka1;
    cout << "masukan angka ke-2: ";
    cin>> angka2;

    besar= angka1 > angka2 ? angka1 : angka2;
    kecil= angka1 < angka2 ? angka1 : angka2;

    cout << endl;
    cout << "angka " << besar << " lebih besar dari angka " << kecil << endl;
    cout << "angka " << kecil << " lebih kecil dari angka " << besar << endl;
}
```
