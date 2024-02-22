# OpenAiChatBot
Chatpot powered by ChatGPT.

Some previous implementations of this project used v3 of OpenAI libraries, so when they updated to v4, a common error was from importing Configuration since it was removed. 
This updated version is adjusted to v4.28.0 of OpenAI.
It is written in Node.js and it runs in the terminal.

# Usage
Make a file named .env and add: OPENAI_API_KEY=YOURKEY

Install dependencies: npm Install

Run the bot: npm start
