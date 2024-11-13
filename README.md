Python Port Scanner 2.0
-------

This is a simple port scanner written in Python that scans the first 100 ports (0-100) of a target IP or hostname and identifies open ports.

Features
---------
Translates a target hostname to its IPv4 address.
Scans ports 0-100 on the target.
Displays open ports.
Provides error handling for invalid hostnames or failed connections.

Prerequisites
-------
You need Python 3 installed on your system. The program uses the built-in socket library, so no additional dependencies are required.

How to Run
----------
Clone or download this repository.

Navigate to the directory where the script is located.

Run the following command in your terminal:

python3 Port_Scanner_2.0.py <target_ip_or_hostname>

Replace <target_ip_or_hostname> with the actual IP address or domain name you want to scan.

python3 Port_Scanner_2.0.py 192.168.1.1


Output Example
----------

Scanning target: 192.168.1.1

Time started: 2024-11-12 12:45:00
_____________________________
Port 22 is open

Port 80 is open

Port 443 is open


Error Handling
-------

If you enter an invalid hostname or IP address, you will see an error message: Hostname could not be resolved.
If the connection to the target fails: Could not connect to server.
To exit the program while it's running, use Ctrl + C, and the message Exiting program. will be displayed.
