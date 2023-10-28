# STRUCTURE
# Name: TARIQ AKHLAK
# PRN: 22070123124

# Structure
A structure is a user-defined data type in C/C++. A structure creates a data type that can be used to group 
items of possibly different types into a single type. 
Structures in C++ can contain two types of members:  
* Data Member: These members are normal C++ variables. We can create a structure with variables of different data types in C++.
* Member Functions: These members are normal C++ functions. Along with variables, we can also include functions inside a structure declaration.

# SYNTAX:
struct structureName{
    member1;
    member2;
    member3;
    .
    .
    .
    memberN;
};

# EXPERIMENT NO: 1
AIM: Find the volume of the cube using structures
ALGORITHM:

--> STEP 1: START
--> STEP 2: Declare and Initialize a structure with required variables
    struct cube {
    double height=2.0;
    double width=4.0;
    double length=6.0;
    
};
--> STEP 3: Access those variables and apply the formula Volume = len*breadth*width
    cube cube1;
    int vol=cube1.height*cube1.length*cube1.width;
--> STEP 4: Print the volume
--> STEP 5: STOP

OUTPUT
The volume of the cube is: 48
