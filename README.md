# Vicinity-ENERC-nodered

Node Red is an opensource visual interface for creating and organizing devices and data flows for the Internet of Things. It has a modular nature and can be integrated with many different protocols, hardware devices, databases, APIs, etc. It was originally developed by IBM but its community has been growing and making it into on of the most used platforms for experimenting with IoT.

# 1. Infrastructure Overview
Due to its popularity, Node Red already comes pre-installed in any version of Raspbian for the Raspberry Pi. 

# 2 - Configuration and deployment
Configuration of Node Red and deployment can be made by following the tutorial here: https://nodered.org/docs/getting-started/

# 3 - Functionality and API
Node Red supports multiple IoT protocols (MQTT, REST APIs, etc.)  and direct interfacing with hardware on the Raspberry Pi. As first approach the HTTP Request Nodes can be used to make GET and POST requests to Vicinity using basic authentication. As a second approach, a custom node can be used for integration of sensors with Vicinity. Development of custom nodes can be seen here: https://www.youtube.com/watch?v=TlzqGhfdbEM
