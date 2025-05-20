# Module 10 Reflection

## Abhiseka Susanto - 2306244942, Class A

### 2.1. Original code, and how it run

![1 server 3 client](1_server_3_client.png)

In the image, the top-left terminal represents the server, while the others are clients. To run the server, use the command cargo run --bin server. To run the client, use the command cargo run --bin client. 

When a client is started, the server detects a new connection from that client—and the same happens for other connected clients. When I type a message in one of the clients, that message is sent to the server, which then broadcasts it to all connected clients, including the sender. That’s why even if only one client sends a message, all clients receive it.