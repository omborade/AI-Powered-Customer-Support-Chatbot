# Customer-Support-Chatbot
This is a basic chatbot designed to provide customer support and answer common questions. The chatbot uses natural language processing (NLP) to understand user input and respond with relevant solutions to common problems.


Features:
Handles common customer support inquiries, such as product information, order status, and return policy
Provides pre-defined responses to common questions and issues
Uses Dialogflow (formerly known as API.ai) for intent detection and response generation
Built using Node.js and Express.js for a scalable and flexible architecture


How it Works:
The user sends a message to the chatbot through a web interface or mobile app.
The message is sent to the server as a JSON payload.
The server uses Dialogflow to detect the intent behind the user's message.
The intent is matched to a predefined response in the chatbot's knowledge base.
The response is sent back to the user as a JSON payload.


Getting Started:
Clone the repository and install the dependencies using npm install.
Set up a Dialogflow project and enable the API.
Create a new agent and import the intents and responses from the intents folder.
Update the dialogflow.js file with your Dialogflow project credentials.
Start the server using node app.js.
Test the chatbot by sending a message to the /customer-support endpoint.
