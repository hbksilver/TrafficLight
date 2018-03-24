# TrafficLight
trafic light program thats only allow one car at a time every 3 seconds, it should start clockwise. 
//Trafic class definition with data members#ifNdef SIM_1_H
#define SIM_1_H

#include <string>
calss Trafic
{
public:
//trafic constructor
Trafic( const std::string&, const std:: string&, const std::string&, const std::string&);
~Trafic();
std::string getRoadOne() const;
std::string getRoadTwo() const;
std::string getRoadThree() const;
std::string getRoadFour() const;

static unsigned int getTimer();
Private:
std::int number_of_cars;
static unsigned int getCycle();
};
#endif

//Trafic class member definition timer and number of cars
#include<iostream>
#include "Trafic.h"
#include<conio.h>


using namespace std;

//global data members
unsined int Trafic::number_Of_cars{0};

//gettor method for # of cars
unsigned int Trafic::getNumber_of_cars()
{
return number_of_cars;
}
//timer
unsigned int Trafic::getTimer()
{
return timer;
}

Trafic::Trafic(const string&roadOne, const string& roadTwo, const string& roadThree, const string& roadFour)
:roadOne(one), roadTow(two), roadThree(three), roadFour(four)
{
string Trafic::getRoadOne() const
{
return roadOne;
}

string Trafic::getRoadTow() const
{
return roadTwo;
}

string Trafic::getRoadThree() const
{
return roadThree;
}

string Trafic::getRoadFour() const
{
return roadFour;
}

// # of cars and timer
while(1)
{
cout<<Enter number of cars: ";
cin>> number_of_cars;
cout<<"\n";

if(num_of_cars==3)
timer=number_of_cars;
else if(number_of_cars>=3)
{
timer = number_of_cars/2;
cycle = number of cars/2;
}
if(t==0)
{
cout<<"Timer is 0.";
else if(t==)
{
cout<<"Timer is 2;
}
else
cout<<"timer is 3";
timer++;
}
return 0;
}


//Trafic lights class
#include<iostream>
#include "Trafic.h"
using namespace std;

boolean Trafic::light
{


//if too many cars
if(number_of_cars>=25 && number_of_cars<=50)
cout<< "Tow many cars decrease waiting time" << endl;

if(timer<3)
cout << "time for cars to pass is to little" <<endl; 

if(light==green)
return true;
else
return false;
}




// data member classtaking number of 
#include<iostream>
#include "Trafic.h";
using namespace
int main() {
cout<< "number of cars is: " 
<< Trafic::getNumber_of_cars() << endl;

Trafic t1{"intersection1", "intersection2", intersection3", intersection4"};

}
