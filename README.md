# brute_froce_adversarial_features_extractor
PCAP Analysis Tool
This tool analyzes PCAP files to extract various features related to login attempts, helping to identify potential security threats.
Installation

Clone the repository:
Copygit clone https://github.com/yourusername/pcap-analysis-tool.git
cd pcap-analysis-tool

Install the package:
Copypip install .


Usage
After installation, you can use the tool from the command line:
Copypcap-analyze <pcap_file> <dst_ip> <dst_port> <output_file>
For example:
Copypcap-analyze captures.pcap 192.168.1.100 443 results.csv
This will analyze the PCAP file, filter for packets to the specified IP and port, and save the results to the output CSV file.
Features Extracted

Login frequency
Inter-login time statistics
Login burst count
Unique source IPs and ports
IP and port entropy
Protocol changes
Username and password attempt statistics
Login success ratio
Account attempt diversity
Packet size statistics
Failed login attempts
Distinct IP-port combinations

Requirements

Python 3.6+
Scapy
NumPy

License
This project is licensed under the MIT License.
