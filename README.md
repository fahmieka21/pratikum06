# pratikum06


Aplikasi Kalkulator sederhana

```
1.Alur algoritmanya
	-Mendeklarasikan string penjumlahan untuk operator aritmatika (+)
	-Mendeklarasikan string penngurangan untuk operator aritmatika (-)	
	-Mendeklarasikan string pembagian untuk operator aritmatika (/)
	-Mendeklarasikan string perkalian untuk operator aritmatika (*)
	-Mendeklarasikan variabel x,y sebagai nilai input
	-Mendeklarasikan variabel hasil untuk hasil aritmatika
	-Mendeklarasikan variabel z untuk nilai input operator aritmatika
```
2.Berikut kode lengkapnya
```

    int main()
{
    cout<<"+++++++++++++++APLIKASI KALKULATOR SEDERHANA+++++++++++++++"<<endl;
    cout<<"                     Fachmi Eka pangestu"<<endl;
    cout<<"                         311810084"<<endl;
    cout<<"                         TI.18.C2"<<endl;
    cout<<endl;
    cout<<endl;
    cout<<"++++++++++++++++DAFTAR OPERATOR ARITMATIKA+++++++++++++++++++"<<endl;
    int x,y,hasil;
    string Jumlah = "1.Penjumlahan (+)";
    cout<<Jumlah<<endl;
    string Pengurangan = "2.Pengurangan (-)";
    cout<<Pengurangan<<endl;
    string Pembagian = "3.Pembagian (/)";
    cout<<Pembagian<<endl;
    string Perkalian = "4.Perkalian (*)";
    cout<<Perkalian<<endl;
    cout<<endl;

    cout<<"Masukan Angka ke-1 :";
    cin>>x;


    int z;
    cout<<"Masukan Operator Aritmatika :";
    cin>>z;

    cout<<"Masukan Angka ke-2 :";
    cin>>y;

    if (z==1)
        {
        hasil=x+y;
        cout<<"Hasil Dari aritmatika ke "<<Jumlah<<","<<x<<" dan "<<y<<" = "<<hasil;
        }
        else if(z==2)
            {
            hasil=x-y;
            cout<<"Hasil Dari aritmatika ke "<<Pengurangan<<","<<x<<" dan "<<y<<" = "<<hasil;
            }
        else if(z==3)
            {
            hasil=x/y;
            cout<<"Hasil Dari Aritmatika ke "<<Pembagian<<","<<x<<" dan "<<y<<" = "<<hasil;
            }
        else if(z==4)
            {
            hasil=x*y;
            cout<<"Hasil Dari aritmatika ke "<<Perkalian<<","<<x<<" dan "<<y<<" = "<<hasil;
            }
            else
                {
                cout<<"Operator Aritmatika Salah";
                }
}
```
3.Flowchart di bawah ini
![img](https://github.com/fahmieka21/pratikum06/blob/master/flowchart.png)

4.Hasilnya Di Bawah Ini
![img](https://github.com/fahmieka21/pratikum06/blob/master/penjumlahan.png)
![img](https://github.com/fahmieka21/pratikum06/blob/master/pengurangan.png)
![img](https://github.com/fahmieka21/pratikum06/blob/master/perkalian.png)
![img](https://github.com/fahmieka21/pratikum06/blob/master/pembagian.png)