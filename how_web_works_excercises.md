# Part One

In your own terms, define the following terms:

- What is HTTP?

    The request-response protocal of the internet. Essentially specifies the standard of how web applications or websites should/will communicate with each other. 
- What is a URL?

    The address of a resource on the internet. 

- What is DNS?

    A server that associates a domain to an IP address.

- What is a query string?

    In a GET request, the query (what is being asked of the server) is stored in the URL itself. 

- What are two HTTP verbs and how are they different?

    Two examples of HTTP verbs are GET request and POST requests. GET requests don't modify anything. Also it's data is stored in the URL as a query, versus the body.  POST requests intend to change data, and it's information is sent in the body of the request. 

- What is an HTTP request?

    A request is a packet of information sent to a server from the client. The request contains information in it's header.

- What is an HTTP response?

    A response is a packet of information sent from the server to the client. Depending on the header of the request, the response could have information in a JSON formt. 

- What is an HTTP header? Give a couple examples of request and response headers you have seen.

    Headers provide additional information in a request or response. Some request headers would be Accept as an example. A response header would be Content-Type. 

- What are the processes that happen when you type “http://somesite.com/some/page.html” into a browser?

    Your browser “resolves” the name into an IP address using DNS
Your browser makes a request to that IP address, including headers (info about browser, any previous cookies, and other things)
The server sends a response (typically, HTML, with a status code (200 if it was sucessful)
The browser makes a DOM from that HTML, and finds any other resources needed (images, CSS, JavaScript, etc)
The browser makes separate HTTP requests for those resources and receives response from the server for each.


