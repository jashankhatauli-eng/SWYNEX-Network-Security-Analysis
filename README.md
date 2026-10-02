# SWYNEX Network Security Analysis

## Objective
The objective of this task was to analyze network traffic in a controlled environment using PCAPdroid on my own Android device.

## Lab Environment
- Device: Android smartphone
- Tool: PCAPdroid
- Environment: Own device and its network traffic

## Protocols Identified

### 1. DNS
- Protocol: DNS over UDP
- Port: 53
- Example: mtalk.google.com
- Purpose: DNS resolves domain names to IP addresses.

### 2. HTTPS
- Protocol: HTTPS
- Port: 443
- Example: dc-stat-in.heytapmobile.com
- Purpose: Provides encrypted communication between the application and server.

### 3. QUIC
- Protocol: QUIC over UDP
- Port: 443
- Example: www.google.com
- Purpose: Provides modern encrypted web transport and is commonly used with HTTP/3.

## Security Observations
The captured traffic showed normal DNS, HTTPS and QUIC connections from applications on my own device.

DNS requests can expose the domains being requested, which may create a privacy concern.

HTTPS and QUIC provide encrypted communication and help protect data during transmission.

No unauthorized systems were tested.

## Evidence
Screenshots of the captured connections and protocol details are included in this repository.

## Conclusion
This analysis helped me understand common network protocols, ports, encrypted traffic and basic network-security observations using a controlled personal-device environment.