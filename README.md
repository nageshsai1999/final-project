# final-project

This is a Restaurant Theme website

The functionalites included in this website are:
1. The user can view the menu page 
2. The user can register to the website and it can create a new account
3. The user can login to the website to their account 
4. The user can add,edit or delete the items(dishes) in the cart page
5. The user can also logout


#Tools used for this website:

FrontEnd:

1.HTML

2.CSS

3.BOOTSTRAP

4.JAVA SCRIPT

5.ANGULAR FRAMEWORK


BackEnd:

1.MYSQL

2.NODE JS

3.API (For Accessing the data in the database)

4.PHP









ERD DIAGRAM:
![ERD diagram (Final Project)](https://user-images.githubusercontent.com/103674487/168941055-0d9405cf-f157-4b08-a550-2c64e490c7d8.jpeg)




A Outlook of the website:

The home page of the website:


![Screenshot 2022-05-17 215513](https://user-images.githubusercontent.com/103674487/168941307-9aead8d3-964a-4bbe-8751-4beae10b54dd.png)




Menu Page:

![Screenshot 2022-05-17 220406](https://user-images.githubusercontent.com/103674487/168942141-b0882af2-5c4d-48dc-a4a9-e2eaf37d497f.png)






About Page:


![Screenshot 2022-05-17 220124](https://user-images.githubusercontent.com/103674487/168941912-3bf91886-aa35-4d57-aa16-0ef9bbbc9454.png)


  Cart Page:
  
  
  ![image](https://user-images.githubusercontent.com/103674487/168942334-0803f8fc-061d-4c61-b81d-57bb8d2702c0.png)


Login Page:


![image](https://user-images.githubusercontent.com/103674487/168942488-5dbd07d6-6717-4143-bd00-f5fad3348e7b.png)



Register Page:



![Screenshot 2022-05-17 220819](https://user-images.githubusercontent.com/103674487/168942668-eff047b2-6a86-42ee-b015-261f1366f8e3.png)



After Login (The items can be added to the cart):

![Screenshot 2022-05-17 221216](https://user-images.githubusercontent.com/103674487/168943085-34dc28c3-cec4-46d4-bac9-01723208e0cb.png)




Steps to Run the Website:

Step 1 : Unzip the final project folder and run the two folders( Open Visual Studio and open two seperate Windows and open Frontend and Backend folder in these two VS windows and run them as I mention them in the following steps. )

Step 2: Install Nodejs for the  project and "Apache server"("PHPMYADMIN" (DATABASE Server)for MySQL Database.

Step 3: Import the given Database file ( restaurantapp(1).sql in Database folder) in phpMyAdmin  .In phpmyadmin after importing the database file. Create a new database named "sai"(had this the database name which I have have given in my code and can be changed according to your configuration which is stored in config file which is situated in Backend folder) ) . It will show two tables which are menu and users where the details of the user are stored.

Step 4: Open the  backend folder in VS code, update the database and user, password in config file and run the command (in VS Terminal) "npm run serve" It will show the database connected successfully.

Step 5: Open FrontEnd folder in new window VS code and run the "npm install" command(in VS Terminal) for importing node_modules.

Step 6: Now run the "ng serve" and the terminal will show the website link, so click on the link and it will take us to our webpage that it's the webpage is ready to use.


Steps to connect the DATABASE To the server:

1.Install "Apache server"  and open the application

![image](https://user-images.githubusercontent.com/103674487/168946524-9e02a51b-49e5-4b0b-b8ac-da068a73ed6a.png)



2. Start the Apache and MYSQL server and press admin (mysql admin button ) where it takes you to the database server

3.Create a new database 

4. Import the database file from the project folder and the server is up and running

![image](https://user-images.githubusercontent.com/103674487/168946965-babc41dc-96ba-477d-8ebd-5b0edd104533.png)

5.Then check if the database is connected successfully in the to the VS code(backend code) by the commands mentioned above.



A final Outlook of the Final Project:

Project : Restaurant App

Web pages like :

	1.Login, 
  
	2.Register, 
  
	3.Home, 
  
	4.Menu and after login and register it'll show Cart page 
  
Register Part: We add userDetails in mySQL database using node with mysql setup(PHPMYADMIN)

Login Part: Verify the user and user able to add items into cart

Menu Page: Fetching Data from Database and shown  in  the menu page

Cart Page: After login user able to add item in cart through menu page

Node+MySQL setup did CRUD operation for user and item 

MySQL :

Database name: sai

Table: 

userdetails : For storing user details and create necessary column for that

menudetails: For Storing menuItem Details and create necessary column for that
  
  
  
  
  Future thoughts for the website:
  
  1.Upgrade the webpage and create a payment portal (mentioned in ERD Diagram)
  
  2.The items would be sent to the check out page
  
  
  


