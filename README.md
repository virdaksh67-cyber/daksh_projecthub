#include <iostream>
using namespace std;

int main() {

int m;// row 
cout<<"enter the rows";
cin>>m;
int n;// coloum
cout<<"enter the coloum ";
cin>>n;
int arr[100][100];
for(int i=0;i<m;i++){ // controle rows 
    for(int j=0;j<n;j++){// controle colums
        cin>>arr[i][j];// input done 
    }
    cout<<endl;
}// now iterat the loop 
for(int i=0;i<m;i++){
    for(int j=0;j<n;j++){
        if(arr[i][j]==0){
            row(arr,i,n);// i smae but j vary as row smae so arr[i][vary ]
            colm(arr,j,m);// j same so i vary arr[vary][colm]
        }
    }

}

for(int i=0;i<m;i++){
    for(int j=0;j<n;j++){
    if(arr[i][j]==-1){
        arr[i][j]=0; // interchange with zero 

    }
}
}

for(int i=0;i<m;i++){
    for(int j=0;j<n;j++){
        cout<<arr[i][j]<<" "; // add " " bw elemtn and aftaer line complete add endl
    }
    cout<<endl;
}
}

return 0;
}

