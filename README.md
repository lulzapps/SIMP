# SIMP

## 0.1- Introduction

SIMP is a JSON-based designed to implement a decentralized instant messaging system. It is designed to be easy to implement and use. There are three different modes of communicatio in which this protocol is used: client-server, server-server and client-client (aka peer-to-peer).

The goals of this protocol are to make is: 

* Lightweight - Optimized for low-latency communication
* Easy to implement - Designed to be easy to implement in any programming language
* Flexible - Support future extensions and modifications
* Secure - Designed with security in mind

### 0.0.1 - Client-Server

This mode is the most common and involves a client, usually an application running on a user's device, or a web-base application running in a user's browser, connecting to a server. The server is responsible for actions such as authentication, sending and receiving messages, and storing messages for offline users.

### 0.0.2 - Server-Server

This mode is used when there are multiple servers that need to communicate with each other. This is useful when a user on one server wants to send a message to a user on another server. In this case, the server that the user is connected to will send the message to the server that the recipient is connected to.

### 0.0.3 - Client-Client

This mode is used when two clients want to communicate directly with each other. This is useful when two users want to communicate without the messages being stored on the server.

## 0.2 - Protocol

The protocol is based on JSON and is designed to be easy to implement in any programming language. The protocol is divided into two main parts: the request and the response. The request is sent from the client to the server, and the response is sent from the server to the client.


