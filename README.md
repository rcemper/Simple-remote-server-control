 ~~~
 This is a coding example working on IRIS 2020.1 and on Caché 2018.1.3 
 It will not be kept in sync with new versions      
 It is also NOT serviced by InterSystems Support !   
~~~ 

This example is extracted from a long-running installation.  
The purpose is to have a simple monitoring of several servers at a rather primitive level.  
Just slightly more intelligent than a raw PING. But still easy to integrate.  
It avoids the overkill of information you are often confronted with while you are just  
interested in the number of active processes or similar basic figures.  
The example shows a basic skeleton that might be easy filled by you real needs.

It consists of 3 sections:

- the data section to hold server access data
- the server section to run unattended at the server you want to monitor
- the client section that is just for demonstration  
  and should be integrated by your code to your environment.
 
Operation is simple:
 
the server starts and listens for requests.

from client various inquiries go to server and get replied.

The whole example is kept very simple and it is your task to add what you require  
and to adapt the client section to your needs and into your environment.

[Article in DC](https://community.intersystems.com/post/simple-remote-server-control)
