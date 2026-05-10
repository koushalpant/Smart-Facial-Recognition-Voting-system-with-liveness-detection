Overview:

The Smart Voting System using Facial Recognition and Liveness Detection is a secure digital voting prototype designed to enhance transparency, authentication, and fraud prevention in electronic voting systems.

This project combines computer vision, facial recognition, and liveness detection techniques to verify voter identity before allowing access to the voting portal. The system aims to reduce risks such as voter impersonation, duplicate voting, and unauthorized access while providing a faster and more efficient voting process.

The project was developed as a prototype to demonstrate how biometric authentication and AI-based verification can improve the security of modern electronic voting systems.

Key Features:
Facial Recognition Authentication:
The system verifies voters using facial recognition technology by matching captured facial data with stored voter records.

Liveness Detection:
To prevent spoofing attacks using photos, videos, or static images, the system performs liveness detection to ensure that a real person is present during authentication.

Secure Voting Access:
Only authenticated and verified users are allowed to cast votes.

Duplicate Vote Prevention:
The system prevents multiple votes from being submitted by the same voter.

Real-Time Camera Verification:
Uses webcam-based verification for live facial authentication.

Database Integration:
Stores voter information, authentication data, and voting records securely using a database system.

User-Friendly Interface:
Provides a simple and responsive interface for voter registration, authentication, and vote casting.

Problem Statement:
Traditional voting systems face several challenges including:

Voter impersonation
Fake identity usage
Multiple voting attempts
Manual verification delays
Security vulnerabilities in voting systems

This project addresses these issues by integrating biometric verification and AI-powered liveness detection into the voting workflow.

Objectives:
Develop a secure and reliable digital voting prototype
Implement facial recognition for voter authentication
Integrate liveness detection to prevent spoofing attacks
Reduce the possibility of duplicate or fraudulent voting
Demonstrate the practical application of computer vision in secure systems

Technologies Used:
Programming Languages
Python
JavaScript
HTML
CSS
SQL

Libraries and Frameworks:
OpenCV
MediaPipe
NumPy
Pandas
Matplotlib
Database
SQLite

Other Tools:
VS Code

System Workflow:
User registers into the system
Facial data is captured and stored securely
During login, the webcam captures live facial input
Facial recognition verifies voter identity
Liveness detection checks whether the face is real and live
If verification is successful, access to the voting portal is granted
User casts vote
System marks voter as “voted” to prevent duplicate voting
Facial Recognition Module

The system processes facial embeddings and compares them against stored facial data in the database to determine identity matches.

Liveness Detection Module:
The liveness detection module helps prevent spoofing attempts using:

Printed photographs
Mobile phone images
Videos
Static face displays

The system analyzes live facial movements and real-time camera input to determine whether the detected face belongs to a real person physically present during authentication.

Database Management:

The database stores:
Registered voter details
Facial data references
Authentication records
Voting status

This helps maintain secure and organized voter management while ensuring that duplicate votes are not allowed.
