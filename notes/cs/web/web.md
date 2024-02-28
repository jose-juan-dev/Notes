# How the Web works

### Intro

- Provides a simplified view of what happens when you view a webpage in a web browser on your computer or phone.

### Clients and Servers

- There are usually two computers connected to the internet, that being clients, and servers.

Clients

- Client devices are usually the typical web user, anyone looking at a site.

Servers

- Servers are computers that store pages, sites, and apps, when a client device wants access to a site,
the site is downloaded from the server and onto the client device to be displayed on the users browser.

### Other parts of the toolbox

Internet Connection

- Allows you to send and recieve data from the web.

TCP / IP

- Transmision control protocol or Internet protocol are communication protocols, that define how the data
being sent should travel across the internet.

DNS

- Domain name system, is the internets address book that connects our urls to the ip addresses of the servers,
Ip is needed to find the needed site servers to send HTTP messages to the right place.

HTTP

- Hyper text transfer protocol, is an application protocol that defines a language for our clients and servers to speak to
eachother.

Component files

- A website is made up of many different files, usually built with HTML, CSS, and JavaScript.

- Can have other assets such as images, music, videos, word documents, and PDF's.

### So what happens exactly

1. You enter url, browser then goes to the DNS server and finds the ip address to the server
that holds the site you want.

2. Once found the browser sends an HTTP request message to server, request ask for
a copy of the site from the server to be sent to the client using TCP or IP.

3. The Server will look at the request and if aprroved it will send the site files to the browser,
in a series of small chunks called data packets.

4. Once the client recieves the packets, the brwoser will begin to assemble the small chunks into a complete,
web page and display it on your browser.

### Parsing order

- When our browser sends a request to the servers, it is impotant to know the order in which they will be read and parsed.

1. The browser will first parse HTML files, which inclide links and needed scripts

2. As the browser is parsing the html, our browser will then send another request for any
css files that may be needed for the site, and lastly any JavaScript files and parse them.

3. The browser then generates an in-memory DOM tree from the parsed HTML, then generates a CSSOM structure
from the parsed CSS, lastly compiles and executes the parsed JavaScript.

4. After the browser builds the DOM tree and applies the needed style from the CSSOM and executes the JS,
the user can now see the entire website and interact with it.

links: [odin], [web]


















