# Hybrid-Wireless-Network-Simulation
**● Project Overview:**

This project simulates a hybrid wireless environment designed in Cisco Packet Tracer. It illustrates two different deployment models:

Enterprise Model: Utilizing multiple Lightweight Access Points (APs) connected to a central switch for high-density client support (Smartphones & Laptops).

Home/SOHO Model: Utilizing a standard Wireless Router for localized connectivity.

<img width="1831" height="690" alt="image" src="https://github.com/user-attachments/assets/198068bf-9de4-4cb1-8054-3bf3ff3466a5" />


**● Technical Features:**

WLAN Infrastructure: Configuration of SSIDs and Wireless security protocols (WPA2-PSK).

Network Segments: Separation of the wireless infrastructure into two distinct wings connected via a central 2911 Router.

Service Integration: Includes dedicated servers (Server 0 & Server 1) likely acting as DHCP, DNS, or HTTP servers to provide network services to wireless clients.

End-to-End Connectivity: Full routing established between the enterprise wing (left) and the home wing (right).

**● Supported Devices:**

The topology manages a variety of end-devices including:

Smartphones (Android/iOS simulation)

Laptops (Wireless NICs)

Desktop PCs (Wired & Wireless)
**● Topology Architecture:**

Core: Cisco 2911 Router.

Distribution: 2960 Switches.

Access: Generic Access Points and WRS300N Home Router.

Clients: Mixed wireless and wired endpoints.

**● How to Use:**

Clone the repository.

Open the .pkt file in Cisco Packet Tracer.

Observe the signal propagation and DHCP address assignment for each wireless client.

Verify connectivity by browsing the HTTP server from a smartphone on either side of the network.
