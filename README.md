Objective

To Emulate a Software Defined Network (SDN) with emerging technologies like 

OpenFlow and SDN using tools Mininet and Open Daylight Controller. There is 

need for dynamic management of network resources for high performance and 

low latency of data transmission in a network.

SDN with OpenFlow is an emerging technology in networking, and with this 

project it is like cherry on the cake, cake being the traditional networking 

concepts of this class.

Tools and Languages Used:

Open Daylight

Mininet

Maven

Python

Expected Output Generation & Analysis:

We are planning on using iperf to generate TCP traffic to test the bandwidth of 

end to end connection. First ICMP 20 packet will be encapsulated with OFP(Open 

flow protocol) and will be sent to the controller. Controller then calculates the 

path with its logic based on statistics collector by the controller and it sends flow 

message back to the switch to program its flow. 

As we will be creating a network by python script in mininet, the output can be 

collected from Open daylight controller and will be seen in GUI.
