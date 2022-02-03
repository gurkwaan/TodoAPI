# TodoAPI
My first api, a TODO-list

Denna Minimala api kan man använder sig av en in-memory databas. Vilket betyder att all data försvinner vid omstart.
För att kunna requesta GET, måste man först ha skickat en POST.

Apin kan använda sig av: GET, POST, PUT och DELETE.


Jag har använt mig av programmet Postman för att skicka mina requests.

- GET https://localhost:[port]/ - Browser test, "Hello World"
- GET https://localhost:[port]/todoitems  - Get all to-do items
- GET https://localhost:[port]/todoitems/{id} - Get an item by ID
- GET https://localhost:[port]/todoitems/complete - Get completed to-do items
- POST https://localhost:[port]/todoitems - 	Add a new item
- PUT https://localhost:[port]/todoitems/{id] - Update an existing item
- DELETE https://localhost:[port]/todoitems/{id}  - Delete an item 



