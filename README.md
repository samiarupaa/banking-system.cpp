//Write a menu-driven banking system (using switch-case) where users can perform
//operations like checking balance, depositing money, withdrawing money
#include<iostream>
#include<conio.h>
using namespace std;
int main()
{ double balance;
int option;
cout<<"1:check balance"<<endl;
cout<<"2:deposit money"<<endl;
cout<<"3:withdraw money"<<endl;
cin>>option;
switch(option){
case 1:
    cout<<"your current balance is: ";
    break;
case 2:
    double deposit;
    cout<<"your deposit balance is: "<<balance+deposit<<endl;
    break;
case 3:
    double withdraw;
    cout<<"enter withdraw balance: ";
    cin>>withdraw;

    if(withdraw<=balance)
        {cout<<"your current balance is: "<<balance-withdraw<<endl;
    }
    else {cout<<"insuffiecient balance";
    }
break;
default:
    cout<<"invalid account";


}
















    getch();
}

