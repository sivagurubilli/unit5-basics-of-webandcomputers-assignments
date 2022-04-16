1)HTML CSS, WEB QUESTION BANK

1)Explain briefly what happens when you hit a url? explain DNS lookup
ans)1)You enter a URL into a web browser
2)The browser looks up the IP address for the domain name via DNS
3)The browser sends a HTTP request to the server
4)The server sends back a HTTP response
5)The browser begins rendering the HTML
6)The browser sends requests for additional objects embedded in HTML (images, css, JavaScript) and repeats steps 3-5.
7)Once the page is loaded, the browser sends further async requests as needed.

2)What is a URLs full form? Explain what a url is and the four parts it consists of The protocol in use The hostname of the server The location of the file The arguments to the file
ans)url is uniform resouse locator a uri is defined as the any character string that identefies a resource. a url is defined as those uris that identify a resource by its location
a url contains four parts 1)a scheme :the scheme identifies the protocol to be used to access the resource on the internet it can be 2) a host: the host name idenifies the host that holds the resource 3) apath: the path identifies the specific resource in the host that the web client wants to access
4)query string: if a query string is used it follows the path component and provides a string of information that the resource can use for some purpose

3)What is HTTP protocol?
ans)HTTP is a protocol for fetching resources such as HTML documents it is the foundation of any exchange on the web and it is a client server protocol which means requests are initiated by the recipient usually the web browser a compleate document is reconstructured fro differnt fetched for instances text layout description images,videos,scripts and more

4)wahat is tcp protocol?
ans)tcp stands for transmission control protocol a communication standard that enables application programs and computing devices to exchange messages over a network. it is designed to send packets across the internet and ensure successful delivery of data and messages over networks

5)explain all diffent http methods
ans)get - the get method requests a representation of the specified resource requests using get should only retrive data
post- the post method submits an entity to the specified resource often causing a change in state or side effects on the server
patch- patch method applies partial modifications to a resource
delete-the deletee method dletes the specified resource

6)what are http headers
ans)http headers let the client and the server pass additional information with an http request or response an http header conssists of its case insensitive name followed by a colon

7)What are some HTTP response codes? what does it mean? 2xx, 3xx, 4xx, 5xx
ans)the response codes are issued by a server in response to a clients request made to the server.1xx is informational response indicates that request was received and understand
2XX - THIS class of status codes indicates the action requested by client was received understand and accepted
3XX- this class of status code indicates the client must take additional action to compleate the request many of theese status codes are used in url redirection
4xx-- this class of status code is intended for situations in which the error seems to have been caused by the the client
5xx -- the server failed to fulfil a requst.

8)What does cache control on http response mean?
ans) cache control is an http header used to specify browser caching policies in both client requests and server responses policies include how a resource is cached where its catched and its maximum age before exppiring

9)what is polling
ans)we wwill take the study of access control methods to the next step and learn about the other method called polling wewill learn about what is polling how transmission of data occurs while polling

10)what is long polling?
ans)it is a technology where the client requests information from server without expecting an immediate response or basically involves making http requess to a server and then holding the connection open to allow the server to respond later

11)what is websockets
ans)a web socket is apersistent connection between a client and server. websockets provide a bidirectional full duplex communication channel that operates over http through a single tcp/ip socket connection the web socket protocol protocol facilitates message passing betwen a client and server

12)how is websockets difernt from http
ans)
