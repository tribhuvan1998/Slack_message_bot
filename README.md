# Slack_message_bot

Slack message bot for a channel in your workspace.

<img src="https://github.com/tribhuvan1998/Slack_message_bot/blob/master/static/Slack_bot.png" width="530" height="400">

## Requirements

- Python 3.6 or higher.
- Create a slack app from [here](https://api.slack.com/apps).

<img src="https://github.com/tribhuvan1998/Slack_message_bot/Static/Create_app.png" width="530" height="400">

- A **Slack App Token**.
- A **Signing Secret**.
- Any Source-Code Editior[I prefer VS Code].
- Download Requirement.txt from above repository.

## Steps

1. Make a folder named Slack bot and open it with VS Code.

<img src="URL" width="530" height="400">.

2. Create a python file [.py extension] named Slack_bot in this folder.  
3. Oen a new **Terminal**.  
4. `pip install virtualenv venv`, to install virtual environment.  
5. `venv\Scripts\activate`, to activate the virtual environment.  
6. `pip install -r requirements.txt`, to install the requirements.  
7. Now copy the source code given in slack_bot.py from the above repository and paste in your Slack_bot in your Editor.  

<img src="https://github.com/tribhuvan1998/Slack_message_bot/Static/Source_code.png" width="530" height="400">

8. Make sure to add functionality and features before getting the Slack Token.

<img src="https://github.com/tribhuvan1998/Slack_message_bot/Static/Create_app.png" width="530" height="400">

9. Features to be added are:
   - Incoming Webhooks (chat:write).
   - Event Subscriptions (channels:history).  
10. Replace **SIGNING_SECRET** and **SLACK_TOKEN** with your own Signing Secret and Slack App Token.  
11. Run the Program.  
12. Host the Program on proper server to use it without any issue.
