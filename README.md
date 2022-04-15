# DiscordBotUsingDiscordJSDoc

Uses discord.js library to create a basic demobot.

https://discord.js.org/#/

note: couldn't get events folder to work despite using the exact code from discord.js documentation. see my notes in index.js for full breakdown.

## Getting Started

Start here: https://discord.com/developers/applications

Click "New Application" - name the Application.

Click "Bot" - "Add Bot"

Go to Oauth2. URL Generator. Click "Bot" and "Administrator" (stick with Administrator for demo purposes)

Copy autogenerated link at bottom of page. Visit the link. Connect the bot to a test server of your choice and close window. Youve connected the bot to your server!

Now, go back to "Bot" and click "Reset Token" to get your token.

Create .env file and add the TOKEN to the file.

Next install dependencies

### Dependencies

npm install

### Executing program

-   Run "npm run dev". This will set up your nodemon server for your bot to run. This should connect your code to the bot.

## Slash commands demoed:

/multiselectdemo and /singleselectdemo two demos of select menus

/ping basic ping "pong" tester

/server gives server info

/user gives user info
