# ProjectGroup4
Project Group 4 for Introduction to Databases

Introduction (Team, Project Description) - 
        This project is for understanding and improving a database system used to provide college students will food delivery services. The intent is to develope and enhance the           database with a rating system for both restaurants and delivery drivers. Our team consists of Andrew and Harmony.

Use Case for Rating System        
Rating systems are a great way to maintain quality assurance amongst the service industry. Therefore, the project will be implementing two methods of rating. One for             rating drivers and the other for rating restaurants. These ratings will allow customers the ability to view the ratings each driver and restaurant has therefore                 helping them make an informed decision. Customers will be given the option of provided a single rating for their driver and a single rating for their restaurant per             order they make.

Business Rules

        1.	Persons (campus faculty, staff, students) have accounts in the system with personid (PK), name, email, cell, etc.  For faculty we also keep title, highest                       degree, and degreecollege.  For staff we keep Position and AdminYorN.  For students we keep GradYear and major plus type (undergraduate, graduate).  Only                         faculty, staff and students are included.
        2.	We have Locations which are spots on campus where food can be delivered.  Some examples are dorms, the student center, and approved classroom buidings.                           LocationID, LocationName, LocationAddress and (optional) Latitude and Longitude are maintained in the database. Additionally a food delivery drop-off point is                   included (designated place for meeting or delivering food in the location – this can be a brief description).
        3.	Persons can also be drivers (delivery personnel which have to be approved). Drivers have licensenumber and datehired plus ratings. You may also want to keep                     vehicle information (relative to the vehicle that the driver uses).
                a.	UNCC will start with 8 approved delivery personnel – the system is in test mode.  You can assume all individuals have been cleared and they can be                               included in the database.  
                b.	All delivery personnel are students.
        4.	There is a flat fee of $5 for each delivery.  A person orders food one to many times.  An individual delivery is tied to one and only one person for the order.                   The order is for one and only one restaurant.  For the items on the order we will only need to keep the total price and delivery charge, along with the driver                   and delivery times.  There should also be a unique identifier (ID) that ties to the id for the order at the indivudual restaurant.  You can assume that the                       actual items on the order need to   come from the restaurant database.
        5.	Food providers or restaurants have to be approved in order to be included in the database.  You can include ten restaurants or more of your choice for the test                   database.  Information will include an ID, location, schedule, and a link to the web site along with other attributes you may identify.
        6.	A driver rating system will be implemented. Each driver will have a driverRating. Drivers will be rated on a scale from 1 – 5. Each customer will have the option                 of giving 1 rating per order for their respective driver.
        7.	A restaurant rating system will be implemented. Each restaurant will have a restaurantRating. Restaurants will be rated on scale from 1 – 5. Each customer will                   have the option of giving 1 rating per order for their respective restaurant.

EERD (full database)
![image](https://user-images.githubusercontent.com/9091474/115177262-d8593780-a09c-11eb-8535-e4a82c62a829.png)


MySQL Queries

A)
![image](https://user-images.githubusercontent.com/9091474/116835194-7665fb00-ab8f-11eb-8b86-a5d392cb7ef6.png)
B)
![image](https://user-images.githubusercontent.com/9091474/116835198-7cf47280-ab8f-11eb-9167-717d97a77ebd.png)
C)
![image](https://user-images.githubusercontent.com/9091474/116835201-81b92680-ab8f-11eb-921d-b8ba605add70.png)
D)
![image](https://user-images.githubusercontent.com/9091474/116835209-85e54400-ab8f-11eb-9084-999ebb883e2a.png)
E)
![image](https://user-images.githubusercontent.com/9091474/116835214-8aa9f800-ab8f-11eb-8648-737d6da1ce0e.png)


Stored Procedure

Stored Procedure Creation
![image](https://user-images.githubusercontent.com/9091474/116835690-91396f00-ab91-11eb-9d2e-9aac9265bd76.png)

Execution of Stored Procedure
![image](https://user-images.githubusercontent.com/9091474/116835670-7961eb00-ab91-11eb-93e1-ce828d7f0f6e.png)


Web/App Implementation or Description of Future Work



MySQL dump

[Sp21.IS3510.Deliverables3.MySQLdump.zip](https://github.com/gamble18/ProjectGroup4/files/6412658/Sp21.IS3510.Deliverables3.MySQLdump.zip)


PPT Video (link)
