# Packet Tracer – Use the ping Command

## Overview
This project demonstrates network troubleshooting using the ping command in Cisco Packet Tracer. The activity investigates why some PCs cannot access a web server and uses connectivity tests and DNS configuration comparisons to identify the problem.

## Objectives
- Test website access from multiple PCs.
- Use ping to test hostname and IP connectivity.
- Inspect DNS configuration using ipconfig /all.
- Correct the affected PC configuration.
- Verify website access after troubleshooting.

## Tools Used
- Cisco Packet Tracer
- Command Prompt
- Web Browser
- IP Configuration utility

## Troubleshooting Procedure

### 1. Test Website Access
Opened the web browser on each PC and attempted to access `www.cisco.pka`.

Recorded which PCs failed to load the webpage.

### 2. Test Hostname Resolution
Executed:

`ping www.cisco.pka`

Compared the output from affected PCs and working PCs.

### 3. Test IP Connectivity
Pinged the web server's IP address directly to determine whether the issue involved general network connectivity or hostname resolution.

### 4. Compare DNS Settings
Executed:

`ipconfig /all`

Compared DNS server information between working and affected PCs.

### 5. Correct the Configuration
Updated the DNS server setting through Desktop > IP Configuration on the affected PCs.

### 6. Verify the Fix
Retested the website using the web browser.

## Key Concepts Learned
- ICMP and ping
- DNS name resolution
- IPv4 connectivity troubleshooting
- DNS server configuration
- Network fault isolation

## Results
Document the affected PC numbers, ping outputs, incorrect DNS settings, and verification results from the completed simulation.

## Skills Demonstrated
Cisco Packet Tracer, network troubleshooting, DNS, ICMP, TCP/IP, and basic network diagnostics.
