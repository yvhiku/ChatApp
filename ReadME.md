# Python Chat Application

## Overview
A real-time chat application built with Python Flask and Socket.IO that allows multiple users to communicate in a shared chat room with customizable usernames and avatars.

## Key Features
- Real-time messaging with Socket.IO
- Random username and avatar generation
- Username customization
- User join/leave notifications
- Responsive and modern UI
- System messages for user events

## Technical Stack
- **Backend**: Python Flask with Flask-SocketIO
- **Frontend**: HTML5, CSS3, JavaScript
- **WebSockets**: Socket.IO for real-time communication
- **Avatar Service**: avatar.iran.liara.run

## Installation

### Prerequisites
- Python 3.7+
- pip package manager

### Setup Instructions
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
Run the application:

bash
python app.py
Open your browser and navigate to http://localhost:5000

File Structure
├── app.py                # Main Flask application with Socket.IO handlers
├── wsgi.py               # WSGI entry point
├── index.html            # Frontend chat interface
├── requirements.txt      # Python dependencies
API Endpoints
WebSocket Events:

connect: Handles new user connections

disconnect: Handles user disconnections

send_message: Broadcasts chat messages

update_username: Handles username changes

Usage
Open the application in your browser

You'll be assigned a random username and avatar

To change your username:

Enter a new username in the input field

Click "Update Username"

To send a message:

Type your message in the input field

Press Enter or click "Send"


License
This project is open-source and available under the MIT License.
