# MULTITHREADED-CHAT-APPLICATION

COMPANY: CODTECH IT SOLUTIONS

NAME: ROHIT THAKUR

INTERN ID: CT12QNE

DOMAIN: JAVA PROGRAMMING

DURATION: 8 WEEKS

MENTOR: NEELA SANTOSH

##

Compile both files:

Copy
javac ChatServer.java
javac ChatClient.java
Start the server first (in one terminal):

Copy
java ChatServer
Start multiple clients (in separate terminals):

Copy
java ChatClient
Features
Basic Chat Functionality: All clients receive messages sent by any client

Multiple Clients: Server can handle many clients simultaneously

Simple Exit: Type "exit" to leave the chat

Thread Safety: Uses synchronization to handle concurrent access

How It Works
The server:

Listens for client connections on port 1234

Creates a new thread for each connected client

Broadcasts messages from any client to all others

Maintains a list of active client connections

Each client:

Connects to the server

![Image](https://github.com/user-attachments/assets/4b74abc6-1b76-4e72-9cc4-7a6eeca7b0aa)

Starts a separate thread to listen for incoming messages

Uses the main thread to send messages to the server

Can disconnect by typing "exit"
