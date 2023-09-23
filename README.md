# Topcho
![Topcho](https://github.com/yasenOfficial/Topcho-Discord-Bot/blob/main/discordbot.png)

# Introduction
Welcome Topcho, a versatile and intelligent bot that utilizes the power of ChatGPT, DALL·E, and Stability AI APIs. This bot enables your Discord server members to generate text that is then converted to speech (TTS), and create images using advanced AI technologies. Whether you want to have engaging conversations, generate creative content, or enhance your server's media, this bot has you covered.

# Features
ChatGPT Integration: Engage in natural language conversations with ChatGPT. The bot can answer questions, provide information, and generate text based on user input.

DALL·E, Stability AI Integration: Generate unique and imaginative images using the DALL·E and Stability AI API. Describe your vision, and the bot will create visuals that match your description.

Text-to-Speech (TTS): Convert text messages into speech and play them in voice channels, enhancing accessibility and interactivity.

Getting Started
Python - make sure you have python 3.11 installed

## API Keys:

ChatGPT API Key &nbsp
Stability AI API Key &nbsp

## Installation

Clone this repository to your server.
```
git clone https://github.com/yasenOfficial/Topcho-Discord-Bot
```


```
cd Topcho-Discord-Bot
```

Install requirements

```
pip install -r requirements.txt
```

Configure the bot by creating a .env file in the project root and adding your API keys and Discord bot token.


```
sudo nano .env
```
paste this:

```
DISCORD_TOKEN=your_discord_bot_token <br />
OPEN_API_KEY=your_chatgpt_api_key <br />
STABILITY_API_KEY=your_stability_ai_api_key <br />
```

Start the bot. Disclaimer! Text to speech (TTS) only works on linux based opperating systems

```
python main.py
```

### Usage
Invite the bot to your Discord server and use the provided commands to interact with its AI capabilities.

### Commands
/generate [message]: Engage ChatGPT in a conversation. Based on the conversation images will be generated by paragraphs and by summarised paraghraps. All of the text generated from the GPT 3.5 LLM is then converted to speech.  <br />
/roll: rolls a dice  <br />
/hello: greets the user and  and shows the time  <br />
/temp: shows the temperature in Stara Zagora  <br />
/help: Display a list of available commands.  <br />

I welcome contributions and improvements to this Discord AI Bot. Feel free to fork the repository, make changes, and submit a pull request.

License
This Discord AI Bot is provided under the MIT License. You are free to modify, distribute, and use it for personal and non-commercial purposes. Please refer to the full license documentation for more details.
