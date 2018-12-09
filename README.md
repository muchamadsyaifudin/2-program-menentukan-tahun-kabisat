#include <iostream>
using namespace std;

void hasil (int x, int y){
     if (x==1){
     	if (y>=17){
     		cout<<"pria dewasa";

     	}
     	else{
     		cout<<"pria belum dewasa";
     	}
     }
     else{
     	if (y>=17){
     		cout<<"wanita dewasa";
     	}
     	else{
     		cout<<"wanita belum dewasa";
     	}
     }

}
int main() {
	int umur,kelamin;

	cout<<"jenis kelamin"<<'\n';
	cout<<"1. laki-laki"<<'\n';
	cout<<"2. perempuan"<<'\n';
	cout<<"masukan pilihan anda (1-2):"; cin>> kelamin;
	cout<<"masukan umur anda (1-100):"; cin>>umur;
	hasil(kelamin,umur);
}
