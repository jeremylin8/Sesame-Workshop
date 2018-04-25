# Sesame Workshop Coding Challenge

Question 1: https://jinweilin8.github.io/Sesame-Workshop/Question-One/questionOne.html

Question 2:
- To add a user, get all users, and delete a user, the URLs that will be used for each function are all “/api/users”. Since RESTful APIs locate the resources associate with user data, the endpoint will be the same for user related function.

-	To add a user, front-end should provide user information object containing name, age, email etc; to get all users, front-end doesn’t need to provide any parameters and to delete a user, front-end should provide the user id.

-	Regardless different front-end libraries/frameworks, we would make a Post request to the server, an example query could be {name: ‘Jeremy’, email: ‘jinwei.lin8@gmail.com’}. Return value will be http status code, in this case, 201 (create), with optional message body.

-	One of 200’s response code such as 200 OK, 201 Created and 204 No Content, along with header and an optional message body.

-	One of 400’s response code such as 400 Bad Request, 403 Forbidden and 404 Not Found.
