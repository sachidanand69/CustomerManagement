# CustomerManagement
I already given the video and screenshot of my assesment by zip file.

#How to run:
if you have eclipse ide , first import that zip file and start the appache tomcat server.
step1. click on customermangement project name and at same time click on right click button.
step2. click on built path
step3. click on select ALL button.
step4. apply all
step5. click on customermangement project name and at same time click on right click button.
step6. click on properties
step7. click on project fecets
step8. set dynamic server as 2.3
step9. run the index1.jsp file which is present inside the src/main/webapp

#frontend Project Details(HTML, CSS, JS)
1) After running the index1.jsp file the login page should be come after enter the valid details into it, the login would be happend.
2) After login ,Home page should come which consist of table and CRUD operation performing buttons.
3) And you can pergform CRUD operation.

#Backend Project details (JSP, Servlets, Springboot)
1) After performing login operation the api should call the login controller and get the data from database and like ID and Password the controller will compare the input data and database data if the condition is true then controller  will move forward and open the jsp file called home.jsp.
2) If you want to add customer then api will call the customer-insert-controller and perform action on adding the new customer into the database.
3) If you want to update customer then api will call the update-controller and perform action on updating the customer into the database.
4) If you want to search customer then api will call the Search-controller and perform action on searching a customer from the data database as per searching requirement.
5) If you want to delete perticular customer then api will call the Delete-controller and perform action on deleting of perticular customer which is present inside database.

#API Testing (technology used: Postman)
1) inserting data into database
   step1. set request is post and write path http://locahost:8080/save
   step2. create the json object and provide the value which wants to store into the database after calling the API.
   step3. Send
2)Login
    step1. set request is GET and write path http://locahost:8080/gets
   step2.  set param values id and password(e.g  id =1 and password= sachin@123)
   step3. Send
3)Get List of Customer
    step1. set request is Get and write path http://locahost:8080/getting
    step2. Send

#Database used(mysql)
