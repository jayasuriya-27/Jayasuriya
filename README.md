# CodeAlpha_BasicNetworkSniffer

A simple network packet sniffer built in Python using Scapy and Tkinter.
It provides a user-friendly GUI to capture, analyze, and summarize packets in real time.

🚀 Features

Start/Stop live packet sniffing with a click.

Displays:

Source & Destination IPs

Protocol (TCP, UDP, ICMP, Others)

Timestamp for each packet

Generates a summary report (packet counts per protocol).

Clean Tkinter GUI interface.

📸 Screenshot


![App Screenshot](https://github.com/Buvanesh-01/CodeAlpha_BasicNetworkSniffer/blob/main/Screenshot%202025-08-26%20223741.png)

🛠️ Requirements

Python 3.8+

Libraries:

scapy

tkinter (comes preinstalled with Python)

📦 Installation

Clone the repository:

git clone https://github.com/your-username/python-packet-sniffer.git
cd python-packet-sniffer


Install dependencies:

pip install scapy

▶️ Usage

Run the script:

python packet_sniffer.py


Click Start Sniffing → begins capturing packets.

Click Stop Sniffing → stops capture and shows summary report.

⚠️ Notes

Requires administrator/root privileges to sniff packets.

On Linux/macOS, run with:

sudo python packet_sniffer.py


On Windows, run from an Administrator Command Prompt.

If you see errors related to Npcap (on Windows), download and install Npcap
.

📊 Example Output
🚀 Sniffing started...

[12:30:12] Packet #1
   From: 192.168.1.5 --> To: 142.250.185.78
   Protocol: TCP (Transmission Control Protocol - used in HTTP, FTP, etc.)

🛑 Sniffing stopped.

📊 Summary Report:
   📦 Total packets: 12
   TCP: 9 packets
   UDP: 2 packets
   ICMP: 1 packets
   Other: 0 packets

📌 To-Do / Future Enhancements

Save captured packets to .pcap file.

Add filters (port, protocol, IP).

Real-time graph of packet counts.

🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to fork this repo and submit a pull request.

📜 License

This project is licensed under the MIT License – see the LICENSE
 file for details.
