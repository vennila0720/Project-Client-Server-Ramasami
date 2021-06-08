# Project-Client-Server-Ramasami

This package consists of an application client-server which has 3 functions:
1. A request to obtain a document which is available on the server.
2. A request to obtain the lost of documents available on the server.
3. A request to delete a document from the list on the server.

When the client is connected to the server, the list of the requests is displayed and thus the client has the ability to choose one of the 3 requests. After choosing the request, the server accept it and process to the request of the client in IPv4 and by using the IP address 127.0.0.1. The connection can take place locally or on devices connected to the same network.

### To install the package
git clone https://github.com/vennila0720/Project-Client-Server-Ramasami.git

### To execute the program
To run the program, we will need to use **2 terminals**. We will do a **cd Project-Client-Server-Ramasami** to go to the directory Project-Client-Server-Ramasami where the files server1.c server2.c client1.c client2.c are located. And then, to execute the program server: gcc -o Project-Client-Server-Ramasami server2.c ./Project-Client-Server-Ramasami and to execute the program client: gcc -o Project-Client-Server-Ramasami client2.c ./Project-Client-Server-Ramasami 
**To be noted that** the program server must first be executed then we can execute the pgram client. If it is done otherwise then the connection between the server and the client will fail.

### Author of the project
Ramasami Vennila
