MERN API 
for backend making API for dashboard
for frontend fetching API for visualizing data



//frontend

1. cd frontend
2. npm i
3. npm start
4. now you go to url http://localhost:3000/
5. now you should see the table along side the section on right for the details of todo list
6. you can sort the table according to column by clicking on the header of the column
7. you can search for whatever you want in the top search bar and it will give results from entire table





//backend

1. make a database in mongodb by the name "productdb"
2. cd backend
3. npm i
4. run the command - nodemon index.js
5. now go to url - http://localhost:5000/api/init   - this will iniatilize the db and transfer data from the API to db
6. now test the APIs one by one

7. for getting Statistics go to http://localhost:5000/api/stats/:month  instead of month give the month you want the data for (eg: for June type http://localhost:5000/api/stats/6)

8. for getting Bar Chart Data go to http://localhost:5000/api/barchart/:month  instead of month give the month you want the data for (eg: for June type http://localhost:5000/api/barchart/6)

9. for getting Pie Chart Data go to http://localhost:5000/api/piechart/:month  instead of month give the month you want the data for (eg: for June type http://localhost:5000/api/piechart/6)

10. for getting All Data from the 3 APIs combined go to http://localhost:5000/api/alldata/:month  instead of month give the month you want the data for (eg: for June type http://localhost:5000/api/alldata/6)