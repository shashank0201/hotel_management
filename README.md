### Hotel Management

It is a small Hotel Management Application which provides interactive python shell.

Tech Stack to be used : Python 3

Task:

A hotel has N number of rooms. Create a list of rooms in the hotel such that
Each room in your rooms list needs to contain at least 5 items (ie, TV, couch, table, Air
Conditioner etc) and the relative dollar value of each item.
It should provide us with an interactive command prompt based shell with the following menu.

1. Add a hotel
2. Add a room to the hotel with any of the 5 items.
3. Print out each room along with the individual items and values. This needs to be
properly formatted, eg: no printing an object as is
4. Accept a budget from the user(in $) and list only those rooms which will cost less than
or equal to his budget.

    

### Setting up a Dev Environment


1. Clone the repo on your local machine and go into the directory:

       $ git clone https://github.com/shashank0201/hotel_management.git
       $ cd hotel_management
       $ pip install -r requirements.txt
       $ python hotel_management.py



Python interactive shell Example:

Enter Hotel name: Taj

Enter Room Number: 111

Enter the amenities name: Tv

Enter amenities prize in $ (should be a number): 10

Enter the amenities name: Sofa


Enter amenities prize in $ (should be a number): 12

Enter the amenities name: Fridge

Enter amenities prize in $ (should be a number): 35

Enter the amenities name: Washing Machine

Enter amenities prize in $ (should be a number): 30

Enter the amenities name: AC

Enter amenities prize in $ (should be a number): 50

Do you want to add more amenities(Yes/No): yes

Enter the amenities name: Table

Enter amenities prize in $ (should be a number): 16

Do you want to add more amenities(Yes/No): no

Do you want to add more Room(Yes/No): yes

Enter Room Number: 222

Enter the amenities name: Couch

Enter amenities prize in $ (should be a number): 19

Enter the amenities name: Tv

Enter amenities prize in $ (should be a number): 9

Enter the amenities name: Table

Enter amenities prize in $ (should be a number): 16

Enter the amenities name: Table Lamp

Enter amenities prize in $ (should be a number): 4

Enter the amenities name: wifi

Enter amenities prize in $ (should be a number): 7

Do you want to add more amenities(Yes/No): no

Do you want to add more Room(Yes/No): no

Do you want to add New Hotel (Yes/No): Marriot

Invalid Input

Do you want to add New Hotel (Yes/No): Marriot

Invalid Input

Do you want to add New Hotel (Yes/No): yes

Enter Hotel name: Marriot

Enter Room Number: 987

Enter the amenities name: iorn

Enter amenities prize in $ (should be a number): 5

Enter the amenities name: Coffee maker

Enter amenities prize in $ (should be a number): 10

Enter the amenities name: Mini Bar

Enter amenities prize in $ (should be a number): 60

Enter the amenities name: TV

Enter amenities prize in $ (should be a number): 10

Enter the amenities name: Fridge

Enter amenities prize in $ (should be a number): 15

Do you want to add more amenities(Yes/No): no

Do you want to add more Room(Yes/No): yes

Enter Room Number: 543

Enter the amenities name: Tv

Enter amenities prize in $ (should be a number): 10

Enter the amenities name: Phone

Enter amenities prize in $ (should be a number): 9

Enter the amenities name: AC

Enter amenities prize in $ (should be a number): 20

Enter the amenities name: Table Lamp

Enter amenities prize in $ (should be a number): 2

Enter the amenities name: Fridge

Enter amenities prize in $ (should be a number): 7

Do you want to add more amenities(Yes/No): yes

Enter the amenities name: Table

Enter amenities prize in $ (should be a number): 9

Do you want to add more amenities(Yes/No): no

Do you want to add more Room(Yes/No): no

Do you want to add New Hotel (Yes/No): no


Taj Hotel have following rooms

Room No 111 have the amenities like Tv, Sofa, Fridge, Washing Machine, AC, Table, and room rent is $153.
Room No 222 have the amenities like Couch, Tv, Table, Table Lamp, wifi, and room rent is $55.

***********************************************************




Marriot Hotel have following rooms

Room No 987 have the amenities like iorn, Coffee maker, Mini Bar, TV, Fridge, and room rent is $100.
Room No 543 have the amenities like Tv, Phone, AC, Table Lamp, Fridge, Table, and room rent is $57.

***********************************************************


***********************************************************

Please enter your budget: 100



Taj Hotel have following rooms matching your budget

Room No 222 have the amenities like Couch, Tv, Table, Table Lamp, wifi, and room rent is $55.

***********************************************************




Marriot Hotel have following rooms matching your budget

Room No 987 have the amenities like iorn, Coffee maker, Mini Bar, TV, Fridge, and room rent is $100.
Room No 543 have the amenities like Tv, Phone, AC, Table Lamp, Fridge, Table, and room rent is $57.

***********************************************************

