## API Intro
### Return all the data in the list
<<<<<<< HEAD
GET http://127.0.0.1:8000/datalist/all/ 200 OK | 404 NOT FOUND
POST http://127.0.0.1:8000/datalist/all/ application/json  201 Created | 400 Bad Request
=======

GET http://127.0.0.1:8000/datalist/all/ 

Response code: 201 Created | 400 Bad Request


POST http://127.0.0.1:8000/datalist/all/ application/json  

Response code: 201 Created | 400 Bad Request

>>>>>>> 29ed08e94acb69a40806724998742032876514b3

### Return by id

GET http://127.0.0.1:8000/datalist/detail/<id>  

Response code: 200 OK | 404 NOT FOUND


PUT http://127.0.0.1:8000/datalist/detail/<id> application/json 

Response code: 200 OK | 400 Bad Request

DELETE http://127.0.0.1:8000/datalist/detail/<id> application/json 

Response code: 204 No Content
