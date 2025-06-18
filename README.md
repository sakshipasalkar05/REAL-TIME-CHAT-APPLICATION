# REAL-TIME-CHAT-APPLICATION

COMPANY: CODTECH IT SOLUTIONS

NAME: SAKSHI PITAMBAR PASALKAR

INTERN ID: CT04DN1197

DOMAIN: FRONT END DEVELOPMENT

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

This is a simple, real-time chat app built using React.js on the front end and WebSockets with Node.js on the back end. It lets multiple users chat instantly in the same room without needing to refresh the page.

When someone opens the app, they’re asked to enter a name. Once they join, they can type and send messages, which appear immediately for all other users who are connected. The chat automatically scrolls down as new messages arrive, making it easy to follow the conversation.

Under the hood, the app uses WebSockets to create a constant, open connection between the client (browser) and the server. This means whenever someone sends a message, the server gets it and sends it out to everyone else — all in real time.

On the front end, React manages things like storing messages, tracking what the user types, and keeping the user interface responsive. It also handles smooth scrolling when new messages come in. The back end is a small WebSocket server using Node.js that listens for messages and shares them with everyone connected.

To run the app, you just start the WebSocket server and the React app in two separate terminals. Open the app in your browser, and it’s ready to go. You can even open it in multiple tabs or browsers to test how messages sync in real time.

This project is a great starting point if you’re new to WebSockets or want to build your own chat app. From here, you could add things like timestamps, avatars, private chat rooms, or even save the chat history using a database.


