# RESTful Web Services

Social Media Aplication

Users -> Posts

- Retrieve all users	- GET 		/users
- Create a user			- POST 		/users
- Retrieve one user		- GET 		/users/{id} -> /users/1
- Delete a user			- DELETE	/users/{id} -> /users/1

- Retrieve all posts for a user - GET /users/{id}/posts
- Create a posts for a user 	- POST /users/{id}/posts
- Retrieve details for a post   - GET /users/{id}/posts/{post_id}