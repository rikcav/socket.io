# Chat Application using Socket.IO

This is a simple chat application built using Socket.IO for real-time communication. Users can send messages to a chat room and join different rooms to chat with specific groups of people.

## Usage

1. Clone the repository:
```sh
git clone https://github.com/rikcav/socket.io.git
```

2. Install dependencies (server):
```sh
cd server
npm install
```

3. Install dependencies (client):
```sh
cd client
npm install
```

4. Start the server:
```sh
cd server
npm run dev
```

5. Start the client:
```sh
cd client
npm run dev
```

6. Open your browser and navigate to `http://localhost:8080` to see the chat application in action.

## Features
- Real-time messaging
- Join different chat rooms
- Simple and clean user interface

## Technologies Used
- **Socket.IO:** For real-time, bidirectional and event-based communication.
- **HTML/CSS/JavaScript:** For the frontend user interface and interaction.
- **Node.js:** For the server-side logic and Socket.IO integration.

## File Structure
- **client:** Contains the client-side code (HTML, CSS, JavaScript).
- **server:** Contains the server-side code (Node.js, Socket.IO).

## Getting Started
1. Open your browser and navigate to `http://localhost:8080`.
2. Enter a username and click 'Join'.
3. Type a message in the input box and press 'Send'.
4. Messages will be displayed in the chat window in real-time.

## Notes
- You can send public messages to all users
- You can join different rooms by entering a room name and clicking 'Join'.
- Messages sent in a room are only visible to users in that room.

Feel free to customize and expand this chat application as needed for your project!
