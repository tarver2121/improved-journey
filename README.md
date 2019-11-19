# improved-journey
These are projects I have done in a C++ course 
//
//  main.cpp
//  shopping _list_vector_tarver
//
//  Created by user1 on 11/15/19.
//  Copyright © 2019 Andrew. All rights reserved.
//Dr Tyson McMillan 
//This is a program that mimics a shopping list 
//Through doing this i have learned more about vectors 

#include <iostream>
#include <vector>
#include <string>
using namespace std;

int main()
{
    string n,a;
    vector<string> shopping_list;
    int i;
    
    cout << " hello user add items to a shopping lise. Type end when you are done" << endl;
    while(a != "end")
    {  cout << " add an item to the shopping cart" << endl;
        cout << " add *** to the front and back of your favorite item " << endl;
        cin >> n;
        shopping_list.push_back(n);
        cout << " do you want to end this program? type end if so " << endl;
        cin >> a;
    }
    
    if(a == "end")
        for(i = 0; i < shopping_list.size(); i++)
            cout << shopping_list[i] << " ";
            
            
            
            }
  
