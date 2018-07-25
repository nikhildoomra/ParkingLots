# Installation Guide #

## 1. Databases ##

### Collections ###


## Entities ##

1 ***Employee*** 
- First Name, 
- Last Name, 
- Emp ID, 
- Emp Email,
- Emp Phone,
- Gender, 
- DOB, 
- Address info, 
- Expecting? etc.
- Roles (lookup)

2 ***Company*** 
- ID
- Name, 
- Parking Lots (lookup)

3 ***Parking Lot*** 
- Address,
- Parking Spots (lookup)

4 ***Parking Spot*** 
- Spot ID
- Spot Number, 
- Parking Lot, (lookup) 
- Floor
- Parking Spot Type (lookup)
- Entrances?? (lookup)

5 ***Parking Spot Type*** 
- ID
- Type
    - Small Vehicle, 
    - Medium Vehicle, 
    - Large Vehicle, 
    - Senior Spot, 
    - Women Spot, 
    - Senior Citizen, 
    - Expecting Women etc.

6 ***Parking Lot Entrance*** 
- ID
- Address

7 ***Vehicle*** 
- Vehicle No., 
- Employee Id, 
- Vehicle Type (lookup)

8 ***Vehicle Type*** 
- ID
- Type
    - Small,
    - Mid, 
    - Large

9 ***Roles*** 
- ID
- Name
    - Administrator, 
    - Employee

10 ***ParkingLog***
-  ID
-  Vehicle (lookup)
-  Parking Spot (lookup)
-  Time In
-  Time Out

## Requirements ##
### Administrator ###
- RA001 - Able to do CRUD ops on all

### Employee ###
- RE001 - Able to park in and park out

- RE002 - Able to edit some info

- RE003 - Able to Edit Vehicle Info

- RE004 - Able to Edit some status values like expecting etc.

- RE005 - Able to check the parking availability

