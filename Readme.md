
# REST

Most of the time in our life we spend on the internet nowadays because we are getting more and more benefits from it, we will see some of its,
- we can do online shopping
- Book our airline tickets, Bus tickets, and Train tickets without going to those places
- Getting news all over the world
- We can transfer money online

whatnot, we are doing amazing things by using the internet just sitting at one place, amazing right. But there are a lot of things in the internet world.
We will understand how the internet works by using one example, let us take Youtube how this works, Before this we will see some parts on the youtube,
1. Frontend
2. REST APIs
3. Server
4. Database

These are the four pillars of any application on the internet. when you click on some video on youtube UI, the rest API takes the request and sends it to the server if the request is successful then the server search in his respective database and send the required information to the Rest API and that API again bring that response to the UI and display in the browser.
Now we will discuss REST one of the crucial parts of this process.

## Introduction to REST

REST stands for Representational State Transfer. Suppose a user search for one product in the application or website. During that time the client(browser) sends that request to the server like hey I want information about this product(like mobile) later when the Server gets the request from the client then the server sends the response to the client with the appropriate information based on the request sent by the client.

If you want to put it in simple words rest is a transfer of the state of the representation of the resource.
REST contains the 6 sets of architectural constraints if take any web service like google, amazon, or Flipkart develops their APIs on top of this REST. we built REST using those 6 constraints in the rest.

## Advantages of REST
Normally we have a client and Server these two are independent of each other to build client-side applications we use react.js,angular.js and for server-side applications, we use node.js or spring. But REST can work smoothly in this case also.
REST is independent of the platform we can use in windows, mac os, and Linux as well, it is not restricted to one format can return XML or JSON, etc.
## Constraints for REST
There are six constraints in REST, those are,
1. Client-Server
2. Stateless
3. Cache
4. Uniform Interface
5. Layered System
6. Code on Demand
we will discuss each of these constraints briefly,
### client-Server
REST applications should have the client-server constrain. A client is the one who does not concern about data storage and only cares about the request for the data the client and sever is the one who does not concern about the business logic and UI. So they can evolve independently.
### Stateless
In this stage whenever the request has happened the client includes all the information regarding the request so that server no needs to maintain the session data. These constraints increase the scalability.
But every time the request needs to send a lot of information so it takes more bandwidth.
### Cache
Cache constrain states responses should be cacheable if possible. it requires that every response should include whether a response can be cacheable or not. It will help you to the client like it can reduce some of the requests from the server.
### Uniform Interface
In this uniform interface, there are three elements that are important.
- Resources are identified using URLs typically
- we can manipulate resources through representation
- self-descriptive message for each request
### Layered System
An application architecture needs to be composed of multiple layers. Each layer doesn't know anything about any layer other than that of the immediate layer and there can be a lot of intermediate servers between the client and the end server. Intermediary servers may improve system availability by enabling load-balancing and by providing shared caches.
### Code on Demand
It is an optional feature. According to this, servers can also provide executable code to the client. The examples of code on demand may include the compiled components such as Java applets and client-side scripts such as JavaScript.
To know more about REST constrains[click here](https://www.geeksforgeeks.org/rest-api-architectural-constraints/)
## conclusion
It is important to create REST API according to industry standards which result in ease of development and increase client adoption.
To know more about REST go through this link[click here](https://youtube.com/playlist?list=PLWPirh4EWFpGRdVZcQCzeTXFBNSTDAdQX)





