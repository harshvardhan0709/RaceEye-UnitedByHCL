# RaceEye-UnitedByHCL

The objective of the project is to build a unique experience for millions of Formula E fans watching the action live at the circuits around the world. It will allow the race-goers to access video feeds from the different cars or any action on the race track beyond their view from the grand stand.

## Features of the app:
1. Rewind and Pause - Allow a user to pause the live stream from the camera and rewind it on the phone.
2. Real Time - Provides near real time stream from the camera.
3. Simple, attractive and easy to use user interface.
4. Centralised control for admin: PHP based web control that helps to configure the camera and the media streaming server. Also, the video settings such as FPS, Resolution can be changed with it.

PLEASE REFER THE SUBMITTED PDF DOCUMENT FOR EASY SETUP

We have achieved this by creating android application along with the web server and media streaming server. All of these being connected to the same Local Area Network. The user requests to the web server for the live stream from the mobile app. The web server then sends a message to the streaming media server, requesting the live stream. Then the streaming server streams the live video to the user’s app, bypassing web server.

All the cameras in the cars are connected to the media server using the wifi. To setup the whole environment we have created a control panel in PHP which will also provide the centralised control for the system.

## Http Server used: Apache/IIS
Media Server used: Zoneminder for Ubuntu server 16.04.2

All the files which are required to setup the servers are uploaded to the GitHub and "source code" section. Please refer the pdf file and "Instruction to Run" section for more details. 

## Future Objective:
1. Increase the number of Livestream in the app from 4 to the number of cars on the race track.
2. Add the live streaming of Race track cameras along with car cameras.
3. Load Balancing: Setup multiple servers and create distributed system that will automatically transfer the user request to other if a server gets overloaded with the requests.
4. Setup a DNS server inside the local area network so that user don't have to manually enter the Ip address of the server in the app.
5. Security: Add more security to the system so that only the authorised persons can access the centralised control, media server and the cameras.
6. IOS APP: We are also working on IOS app. Right now it is incomplete. We will complete it in the future.
7. Merging the project with the official formula E app: If possible we try to merge this project with the Formula E app.

PLEASE REFER THE SUBMITTED PDF DOCUMENT FOR EASY SETUP
