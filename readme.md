### http
http is hyper text transfer protocol
it is a protocol for transfering data 
it is a request/response based protocol
where normally the client a web browser sends an http request to a server and expects to recieve back an http response
the request will have things like headers and paramaters and the response will have somethings like headers a body and status code

###/user/1
the routing would indicate that you are refferencing the user with id of 1
if you hit this with a GET request a RESTful server should return the user with the id of 1
if you hit this with a PUT request a RESTful server would be expecting you to have included a payload in your request which the RESTful server can use to update the data of user with the id of 1
if you hit this with a DELETE request a RESTful server should attempt to delete the user whose id is 1

###/users
if you hit this with a GET request a RESTful server should get all the users
if you hit this with a GET request in query paramaters the RESTful should get the users that match that criteria
