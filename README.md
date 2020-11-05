**Microsoft Teams Online Class Attender**

This bot attends the online classes (or meetings) held on Microsoft teams, according to the given timetable.

**Configure**

There are few things you need to configure before running this bot.

- Open Microsoft teams on your browser, login to your account, change the dashboard view to list view (from grid view), so that your classes are displayed in a list view.
- Open bot.py, and put your microsoft teams credentials in the CREDS dictionary.
- Example - CREDS = {'email' : 'myemail@email.com', 'passwd':'''mypassword'''}
- Open discord_webhook.py and put your discord webhook URL in the webhook_url variable.
Example - webhook_url = "https://discordapp.com/...."

**Install**

- Clone the repository git clone https://github.com/tomassabol/MS-Teams-Attender
- Install requirements.txt pip install -r requirements.txt

**Run the Bot**

- Run the bot python bot.py
