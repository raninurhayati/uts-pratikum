# uts-pratikum


#soal 1

*Alur algoritma*

1.Deklarasi variabel 'int A,B.X,Y'
2.Maukan input 'cin >>A >> B'
3.Deklarasi nilai 'x = A: Y=B'
4.Bandingan apakah 'x<Y'
5.Bila langkah ke-4 bersifat **true** bandingkan apakah 'x < Y'
6.Bila nilai 'x' lebih kecil dari 'Y' maka jalankan perintah 'X=X+A bila tidak maka dijalankan perintah 'Y=Y+B
7.cetak >>X'

*berikut code lengkapnya*
```
#include<iostream>

using namespace std;

int main() {
    int A, B, X, Y;

    cout << "Masukkan nilai A: ";
    cin >> A;

    cout << "Masukkan nilai B: ";
    cin >> B;

    X = A;
    Y = B;

    if (X!=Y) {
        if (X<Y){
            X=X+A;
        } else {
            Y=Y+B;
        }
    }

    cout << X;
}
```

## soal 2

*Alur algoritma*

1.Deklarasi variabel 'int N,X,T BATAS;
2.Maukan input 'cin >> N'
3.Deklarasi nilai batas = N+100:X =20:T=N
4.Selama kondisi 'T<= Batas masih bersifat  **true** maka akan dkerjakan 'T =T + X=X =X +10
5 Cetak 'cout <<T


*berikut code lengkapnya*
```
#include<iostream>

using namespace std;

int main() {
    int N, X, T, Batas;

    cout << "masukan nilai n";
    cin>> N;

    Batas = N + 100;
    X = 20;
    T = N;

    while ( T <= Batas ) {
        T= T+X;
        X=X+10;
    }

cout<< T;

}
```


