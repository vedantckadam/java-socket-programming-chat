# java-socket-programming-chat
Mini networking project in Java demonstrating client-server communication using socket programming.
A simple client-server chat application built using Java Socket Programming.  
This project demonstrates real-time communication between a client and a server using TCP sockets.

## Features
- Two-way communication between client and server
- Built using Java networking concepts
- Uses `Socket` and `ServerSocket`
- Console-based chat interface
- Easy to understand for students and beginners

## Technologies Used
- Java
- Socket Programming
- TCP/IP Networking

## Project Structure

```bash
├── ChatServer.java
└── ChatClientt.java
```

## How It Works
1. The server starts and listens on port `2100`
2. The client connects to the server using localhost
3. Both can send and receive messages in real-time
4. Type `end` on the client side to close the connection

## How to Run

### 1. Compile files
```bash
javac ChatServer.java
javac ChatClientt.java
```

### 2. Start Server
```bash
java ChatServer
```

### 3. Start Client
Open another terminal and run:

```bash
java ChatClientt
```

## Sample Output

### Server
```text
Server Application is Running.....
Server is Waiting at port 2100
Client Request gets Accepts Successfully
```

### Client
```text
Client Application is Running.....
Connection is Successful with Server
```

## Learning Concepts
This project covers:
- Client-Server Architecture
- TCP Communication
- Java I/O Streams
- Networking Basics

## Author
Vedant Kadam
