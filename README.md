 # Cloud-Computing-Learning
The Basics of Cloud Computing

Cloud Computing

EC2 - Elastic Compute Cloude 2
Amazon EC2 (Elastic Compute Cloud) is a core AWS service that lets you rent secure, resizable virtual servers—called instances—on demand. It provides scalable computing power without needing to buy physical hardware, making it the backbone of most cloud applications today.

IAAS - Infrastructure As a Service


What is cloud computing?

Cloud computing refers to the delivery of computing resources—such as servers, storage, databases, networking, software, and analytics—over the Internet (“the cloud”) so that individuals and businesses can use powerful computing tools without owning or managing physical hardware themselves.

Key Concepts

1. On-Demand Internet Delivery
Instead of storing data or running software on your own device or local server, cloud computing lets you access these resources over the internet from remote servers maintained by cloud providers.

2. No Large Upfront Costs
With cloud computing, you typically pay only for the services and resources you use (pay-as-you-go), eliminating the need to buy and maintain expensive hardware.

3. Scalability and Flexibility
Cloud resources can be scaled up or down quickly based on demand. This means you can get more power or storage when you need it, and reduce it when you don’t, without manual hardware changes.



What is IAM ?

IAM is a serivce that helps you securely control access to AWS resources. 
It allows you to manage users, roles, and permissions to define who can access what within your AWS environment.

Create users : You can create individual user accounts for people who need
 access to your AWS resources.

 Assign Permission : You can Assign specific permission to users, groupsm or 
 control what action they can perform on AWS serivces.

 Create Groups : You can group user together and assign permission to the group, making management easier for multiple users.'

Create Roles : You can create roles to assign temporarry permission to aws services or users, especially for securely managing permissions accross different AWS resources.

Define Policies : You can create and attach custom policies to define finegraned permisions for controlling access to AWS resources.

Manage Federated Access : IAM allows intergrating with external identity providers like Active diroctory for centralized management of users access accross AWS.

MFA :- MFA (Multifactor Authentication) is an extra layer of security that requires users to provide two or more forms of verification,, like a password and a code from their phone, to access their accpunts.  


Function as a Service (FaaS)
The Service provider handles all of the infrastructure, including servours, networking, and storage.


Networking : It refors to connecting two or more computers and devices together so they can share data, resources and services such as a files , printers m internet access , and more.

In computer network , protocols (rules for communication) ensure taht devices understand each other and exchange information correctly. examples include TCP/IP, HTTP and FTP

There are types of networks :
LAN
WAN
MAN
LAN:- That is refers to a Local area network that is coverd neaby your house and the cover area about 100 to 200 sq ft area.
WAN :- A wireless version of LAN using Wi-Fi technology.
Devices connect without cables ,Common in homes, schools, and public hotspots.
MAN:- Metropolitan Area Network , Covers a larger area ( a city , campus , or town) than a LAN but smaller that a WAN.
oftern used by city govt, or large organisation.


OSI Model : Open Systems Interconnection Model

The 7 Layers of the OSI Model (Top → Bottom)

Application Layer

Closest to the user; provides network services to applications (e.g., web browsers, email clients).

Examples: HTTP, FTP, SMTP.

Presentation Layer

Converts data formats, handles encryption/decryption and compression.

Makes sure the data from the sending system can be understood by the receiving system.

Session Layer

Manages and controls dialogue (sessions) between two devices.

Responsible for establishing, maintaining, and terminating connections.

Transport Layer

Ensures reliable transmission of data between devices.

Handles segmentation, flow control, and error checking.

Common protocols: TCP, UDP.

Network Layer

Responsible for data routing and addressing across networks.

Assigns logical addresses (e.g., IP addresses) and forwards packets.

Data Link Layer

Ensures error-free communication between devices on the same network.

Frames data and manages physical addressing (MAC).

Physical Layer

Deals with the physical transmission of bits over cables, fiber, or wireless.

Defines electrical, mechanical and procedural specs (e.g., connectors, cables)


The most important topic is OSI model.

The TCP/IP Model
The TCP/IP model is the network model used in the current Internet Architecture.
It is a concise version of the OSI mpdel. Therefore, the layers in the TCP/IP protocol suite do not match exactly with those in the OSI model.
The original TCP/IP protocol suite was defined as four software layers built upon the hardware.

Difference b/w tcp &IP




 



 







