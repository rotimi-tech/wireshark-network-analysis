# Wireshark Network Analysis Notes

## Objective
The purpose of this project was to capture and analyze live network traffic using Wireshark to understand network communication and packet behavior.

## DNS Analysis
The DNS filter was used to observe domain requests and responses. Traffic involving YouTube domains such as `accounts.youtube.com` and `www.youtube.com` was captured. DNS packets demonstrated how domain names are translated into IP addresses.

## TCP Analysis
The TCP filter displayed communication between systems and showed packet flow between source and destination devices.

## TCP Handshake Analysis
Using `tcp.flags.syn == 1`, SYN, SYN-ACK, and ACK packets were identified to observe the TCP three-way handshake process.

## HTTPS/TLS Analysis
Traffic on port 443 displayed encrypted communication using TLSv1.3. Client Hello messages and secure traffic patterns were observed.

## Conclusion
This project strengthened my understanding of packet analysis, DNS behavior, TCP communication, troubleshooting, and Wireshark filtering.
