# Books-management-Software
This is combination of frontend GUI as well as backend and then I linked frontend buttons with backend.
This repo contains 3 things.
    1.Frontend script
    2.Backend script
    3.All in one software with full GUI mad ewith python.
    
    
Frontend:
Simple functions(label(),button()) with arguments as window,text="" etc. enlosed in windows.tk()
Position them with .grid funtion.<<<grid(row=4,column=2)>>>
To link front end buttons with backend,use wrapper functions.

Backend:
Use function for all buttons that you want to work with backend.
Steps of functions:
1.Connect to database.
2.Create a cursor object of connection
3.Execute an SQL query using cursor object
4.Commit changes (using onnection)
5.Close connection (using connection)


