# TCP Echo Client/Server

A TCP echo client and server demonstrating socket programming, connection lifecycle, and graceful shutdown.

## Overview
Built as part of Columbia University's Computer Systems course (COMS 3157). The client connects to a server, sends messages, and receives them back; the server echoes each message to its client.

## Tech Stack
- **Language:** C
- **Protocols:** TCP/IP
- **System Calls:** socket, bind, listen, accept, connect, recv, send

## Key Features
- **Server:** accepts connections, echoes received messages, handles multiple clients sequentially
- **Client:** connects, sends user input, prints server response
- **Graceful shutdown** on connection close or error
- **Signal handling** for clean termination
- **Network byte order** handling (htons, htonl, ntohs, ntohl)

## What I Learned
- TCP socket lifecycle (create → bind → listen → accept → communicate → close)
- Client-server architecture
- Network byte order and address structures
- Error handling in systems programming

## Note
This project was completed for a course. Source code is available upon request due to course policy restrictions. I'm happy to discuss the socket programming and protocol handling in an interview.
