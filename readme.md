# Computer Networking Fundamentals

## 1. Domain Name vs Host Name

### Domain Name

- A domain name identifies a website on the internet
- Example: In "https://www.example.com", "example.com" is the domain name
- Domain names are part of the DNS system
- They provide a human-readable way to access websites

### Host Name

- A hostname identifies a specific device or server within a network
- Example: In "username@example.com", "username" is the host name
- Hostnames are used for internal network identification

## 2. Computer Network

A computer network is a system of interconnected devices that can communicate and share resources with each other. It includes:

- Computers
- Servers
- Printers
- Routers
- Other networked devices

### Key Benefits

- Resource sharing
- Communication
- Centralized data management
- Cost efficiency

## 3. Internet

The Internet is a global network of networks that connects millions of computers worldwide. Key characteristics:

- Uses standardized communication protocols (TCP/IP)
- Enables global data exchange
- Connects various types of networks
- Provides foundation for services like email, web browsing, and file sharing

## 4. World Wide Web (WWW)

The World Wide Web is an information system built on top of the Internet infrastructure:

- Collection of interconnected documents and resources
- Accessed via web browsers
- Uses HTTP/HTTPS protocols
- Identified by URLs
- Includes websites, web pages, and web applications

## 5. Domain Name System (DNS)

DNS is the internet's phone book, translating human-readable domain names into IP addresses.

### Key Functions

- Domain name resolution
- Hierarchical naming structure
- Distributed database system
- Cache management

Example:

```
www.example.com ➡️ 93.184.216.34
```

## 6. IP Address

An IP address is a unique numerical identifier assigned to each device on a network.

### Types

1. IPv4: 32-bit address (e.g., 192.168.1.1)
2. IPv6: 128-bit address (e.g., 2001:0db8:85a3:0000:0000:8a2e:0370:7334)

### Purpose

- Device identification
- Network routing
- Location addressing
- Network interface identification

## 7. Port Numbers

Port numbers are 16-bit integers that identify specific processes or services on a computer.

### Common Ports

- HTTP: 80
- HTTPS: 443
- FTP: 21
- SSH: 22
- SMTP: 25

### Purpose

- Process identification
- Service multiplexing
- Traffic routing
- Application addressing

## 8. Protocols

Protocols are standardized rules for data communication in computer networks.

### Key Aspects

- Data format
- Error handling
- Flow control
- Connection management
- Security measures

## 9. TCP/IP Protocol Suite

TCP/IP is the fundamental protocol suite of the Internet.

### TCP (Transmission Control Protocol)

- Reliable data delivery
- Error checking
- Ordered packet delivery
- Connection-oriented communication

### IP (Internet Protocol)

- Routing
- Addressing
- Packet forwarding
- Network segmentation

### Common TCP/IP-based Protocols

- HTTP: Web browsing
- SMTP: Email transmission
- FTP: File transfer
- SSH: Secure shell

## 10. WebSocket

WebSocket is a communication protocol that provides:

- Full-duplex communication
- Single TCP connection
- Real-time data transfer
- Persistent connection

### Use Cases

- Chat applications
- Live feeds
- Gaming
- Real-time dashboards

### Benefits

- Reduced latency
- Lower overhead
- Bi-directional communication
- Server push capability

Example WebSocket Connection:

```javascript
const ws = new WebSocket("ws://example.com/socketserver");

ws.onopen = () => {
  console.log("Connected to WebSocket server");
};

ws.onmessage = (event) => {
  console.log("Received:", event.data);
};
```

## Summary

These networking concepts form the foundation of modern internet communications:

- Domain names and hostnames provide human-readable addressing
- Networks enable device interconnection
- The Internet connects networks globally
- WWW provides information access
- DNS translates names to addresses
- IP addresses identify devices
- Ports identify services
- Protocols standardize communication
- TCP/IP enables reliable data transfer
- WebSockets enable real-time communication

Understanding these concepts is crucial for:

- Web development
- Network administration
- System architecture
- Application design
- Security implementation
