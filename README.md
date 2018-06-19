# ms3-challenge-api
This is to create a range for the two input parameters submitted and replace values mentioned in te problem statement

 # Problem Statement:

A client has requested a web application that calls an API-enabled backend utilizing an algorithm.  The backend algorithm takes in 2 integers representing a range, and converts each number in the range. Multiples of 7 convert to “MS3”, multiples of 3 convert to “ME”, and multiples of both 7 and 3 convert to “MS3 and ME”.  The algorithm should be created in the most optimized way possible. The input range has a limit from a minimum of 1 to a maximum of 200. Ideally, users should be able to query inputs HTTP API calls.  Responses should be in the form of JSON,


# Software requirements to run the code.
  1) MuleSoft anypoint studio 3.9 runtime
  2) postman rest client to test the api
  
API endpoint : localhost:8081/api/ms3-challenge
we need to add 2 query parameters to the endpoint
  1) int1
  2) int2
  
int1 and int2 values should be integer

example of the endpint uri with query parameters 
 localhost:8081/api/ms3-challenge?int1=0&int2=200

open postman and enter the uri in the postman client.
