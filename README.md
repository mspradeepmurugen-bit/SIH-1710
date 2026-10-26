# Smart India Hackathon Workshop
# Date:26/10/2026
## Register Number:212225220071
## Name:Pradeep.M
## Problem Title
SIH 1710: Enhancing Navigation for Railway Station Facilities and Locations
## Problem Description
Background: Railway stations are complex environments with numerous facilities and locations such as ticket counters, platforms, restrooms, food courts, and waiting areas. Passengers often face difficulties in navigating these spaces, especially in large or unfamiliar stations. Efficient and user-friendly navigation systems are crucial for improving passenger experience, reducing congestion, and ensuring timely travel connections. Description: The problem involves developing a comprehensive navigation solution for railway stations that assists passengers in locating various facilities and destinations within the station premises. This includes creating detailed maps, providing real-time directions, and integrating features such as accessibility options for individuals with disabilities. The solution should be intuitive, easy to use, and accessible via multiple platforms, including mobile devices and digital kiosks. Key challenges include updating navigation information in real-time, ensuring accuracy, and accommodating the diverse needs of all passengers. Expected Solution: The expected solution is a multi-platform navigation system that provides detailed, real-time directions to all facilities and locations within a railway station. This system should include: A mobile application with 3D interactive maps and step-by-step navigation. Digital kiosks located throughout the station with touch-screen interfaces. Voice-guided navigation for visually impaired passengers. Regular updates to reflect changes in station layout and facility locations. Integration with existing railway apps and services for seamless user experience. The solution should enhance the overall passenger experience by reducing confusion, saving time, and improving accessibility within the station.

## Problem Creater's Organization
Ministry of Railway

## Idea
Build a web and mobile-friendly application that helps passengers find any facility inside a railway station and guides them along a suitable route.

The special feature is QR-assisted indoor navigation with accessibility-aware route planning and multilingual voice guidance.

Unlike ordinary map applications, which may struggle to locate passengers precisely inside buildings, RailNav 360 uses a mapped station network and QR codes placed at known locations to help establish the passenger's position.

## Proposed Solution / Architecture Diagram
<img width="437" height="512" alt="image" src="https://github.com/user-attachments/assets/a2cbf7df-e81e-45ec-9897-e79fd4ee291b" />


## Use Cases
Find railway station facilities such as platforms, restrooms, ticket counters, food courts, and waiting rooms.
Navigate inside railway stations using interactive maps and step-by-step directions.
Scan QR codes to identify the passenger's current location.
Provide voice-guided navigation in multiple languages.
Find wheelchair-accessible routes using ramps and lifts.
Update facility information and reroute passengers when paths are closed.
Support navigation through mobile applications, websites, and digital kiosks.

## Technology Stack
## Frontend:
HTML, CSS, JavaScript
## Backend:
Python Flask
## Interactive Maps:
Leaflet.js / SVG maps
## Route Calculation
Dijkstra's algorithm
Database	SQLite
## Location Identification	
QR codes
##Voice Assistance:
Speech Recognition and Text-to-Speech
## Dependencies
Python libraries:
- Flask – Backend web framework
- qrcode – Generate QR codes
- opencv-python – Scan and detect QR codes using a camera
- networkx – Calculate routes using graph algorithms
Frontend libraries and tools:
- Leaflet.js – Interactive maps
- HTML, CSS, and JavaScript – User interface
- Browser Speech API – Voice input and spoken directions
