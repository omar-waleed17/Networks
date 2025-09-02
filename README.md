# Networking Projects – Torpedo Technical Team Training

This repository contains networking projects completed as part of the **Torpedo Technical Team training**, designed to help us learn and practice **Python socket programming**, client-server communication, and network reliability concepts.

## Part 1 – UDP Packet Transmission Simulation

- Implements a **UDP client-server system** simulating packet transmission.  
- The **server** responds to packet requests but randomly drops packets to simulate **packet loss**.  
- The **client** sends sequential packets and **resends lost packets** based on a timeout mechanism.  
- Demonstrates key concepts such as:
  - UDP communication  
  - Handling **timeouts**  
  - Implementing a simple **retransmission mechanism**  

## Part 2 – TCP File Transfer System

- Implements a **TCP client-server system** for **uploading and downloading files**.  
- The **server** listens on a port, handles multiple clients using **threads**, and processes requests concurrently.  
- Supports **HTTP-like requests**:
  - `GET` requests for downloading files  
  - `POST` requests for uploading files  
- The **client** provides a simple menu to upload or download files and handles server responses.  
- Demonstrates key concepts such as:
  - TCP socket programming  
  - File transfer over the network  
  - Threaded server for handling multiple clients  
  - Simple HTTP-like request handling  

These projects provide practical experience in **network programming, reliability mechanisms, and client-server design**, forming a strong foundation for more advanced networked applications.
