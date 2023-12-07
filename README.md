# MQTTinl-mning2

MQTT Chat Application
Summary:

This Python script is an MQTT-based chat application developed as part of a school project. It enables users to participate in chat rooms and engage in real-time conversations within selected chat groups. The application connects to an MQTT broker, allowing users to send and receive messages while being able to join different chat rooms.

Key Features:

Chat Room Selection: Users can choose from different chat rooms, such as "python," "cooking," or "gaming," to engage in conversations relevant to their interests.

Real-time Messaging: The application provides real-time messaging capabilities, allowing users to send and receive messages in their chosen chat room.

User Interaction: Users can enter their username and select a chat room to start chatting.

Customized Messages: Users can send personalized messages and use the /me command to send actions.

Graceful Exit: The application handles user exits gracefully, sending notifications when users join or leave chat rooms.

Threaded Input: Input from users is processed using a separate thread to ensure continuous message reception and sending.

How to Use:

Execute the script in your Python environment.

Enter your desired username when prompted.

Select a chat room from the available options.

Start chatting with others in real-time.

Type "/me" followed by an action to send actions in the chat.

Type "quit" to exit the chat room and the application.

Technology Used:

Python
Paho MQTT library
MQTT broker (broker.hivemq.com)
Enjoy real-time chatting with others in the selected chat room!
