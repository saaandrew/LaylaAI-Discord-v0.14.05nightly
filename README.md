# LaylaAI - Snapshot 051323nightly
This is a [Python](https://www.python.org)-based Discord bot using the `discord.py` library. The bot responds to messages, can change its profile picture, and provide latency information. Additionally, it uses the `theb` from [GPT4FREE](https://github.com/xtekky/gpt4free) for generating responses based on conversation history.


## Commands ⚙️⚙️
- For all commands use `/help` in discord
# Steps to install and run 🚩 :
### Step 1. 🎬 Git clone repository
```
git clone https://github.com/saaandrew/LaylaAI-DiscordBot
```
### Step 2. 📁 Changing directory to cloned directory
```
cd LaylaAI-DiscordBot
```
### Step 3. 🔑 Getting discord bot token and enabling intents from [here](https://discord.com/developers/applications)

### Step 4. 🔑 Get hugging face Access Tokens from [here](https://huggingface.co/settings/tokens)
## Read or Write it dosent matter
![image](https://user-images.githubusercontent.com/91066601/236681615-71600817-774a-430c-8cec-8e6710a82b49.png)

### Step 5. 🔐 Rename `example.env` to `.env` and put the discord token and hugging face access token. It will look like this:
```
HUGGING_FACE_API=hf_access_token_from_step_4
DISCORD_TOKEN=token_from_step_3
```
### Step 6. ⚙️ Install all the dependencies
```
pip install -r requirements.txt
```
### Step 7. 🚀 Run the bot
```
python main.py
```
### Step 8. Invite the bot
![image](https://user-images.githubusercontent.com/91066601/236673317-64a1789c-f6b1-48d7-ba1b-dbb18e7d802a.png)


### 🏁 Finally talk to the bot
#### There are 2 ways to talk to the ai
- Invite your bot and DM (Direct message) it | ⚠️ Make sure you have DM enabled
- if you want it in server channel use **/toggleactive** 
- For more awesome commands use **/help**

# ✨✨✨  Other ways to run ✨✨✨

### Using docker to run :whale:
- Have a working bot token
- Follow up-to step 5
#### Install docker compose on linux machine :
```
apt update -y ; sudo apt upgrade -y; sudo apt autoremove -y; sudo apt install docker-compose -y
```
#### Start the bot in docker container :

```
sudo docker-compose up --build
```
### Using replit to run ☁️
- Follow all the steps except `step 1`
- Have a replit account
- Please note `.env` found in secrets tab of replit :

![image](https://user-images.githubusercontent.com/91066601/235810871-5d4c1469-35fd-42d2-a3a2-3382002877cb.png)

- Config `secrets` in replit like this :

![image](https://user-images.githubusercontent.com/91066601/235811115-689c40e8-660a-448d-83dd-194631324436.png)

# [![Try on repl.it](https://repl-badge.jajoosam.repl.co/try.png)](https://repl.it/github/saaandrew/LaylaAI-DiscordBot)

