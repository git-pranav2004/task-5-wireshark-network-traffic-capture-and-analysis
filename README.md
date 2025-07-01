# Task 5 - Wireshark Network Analysis

# Objective:
To capture live network traffic and analyze different protocols using Wireshark.

# Tools Used:
  •	Wireshark v4.4.7 (mention your version)
  •	Browser (Chrome/Edge)
  •	Windows CMD (ping utility)

# Protocols Identified:
  1. DNS (Domain Name System)
    •	Purpose: Resolves domain names to IP addresses.
    •	Activity: Observed DNS Query & Response packets.
    •	Example:
      o	Query: google.com
      o	Response: Returned IP like 142.250.195.110
    •	Insight: Each time a new domain is accessed, a DNS lookup is initiated unless cached.

  2. TCP (Transmission Control Protocol)
    •	Purpose: Ensures reliable, ordered delivery of data between devices.
    •	Activity: Observed TCP Handshake (SYN, SYN-ACK, ACK) and normal segment transfers.
    •	Example:
      o	HTTP traffic over TCP port 80 or HTTPS over port 443.
      o	Stream between local IP and example.com
    •	Insight: TCP ensures connection reliability — essential for web, email, and file transfers.

  3. ICMP (Internet Control Message Protocol)
    •	Purpose: Used for diagnostics and error reporting (e.g., ping).
    •	Activity: Sent ping to google.com and captured Echo Request and Echo Reply.
    •	Example:
      o	ICMP Request → 8.8.8.8
      o	ICMP Reply from 8.8.8.8
    •	Insight: Helps determine if a host is reachable and measures latency.

# Key Learnings:
  •	Understood packet structure and protocols.
  •	Learned to apply filters in Wireshark.
  •	Gained practical hands-on with packet capture and analysis.
