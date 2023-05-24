This is a simple script to add events in Google calendar
This creates event "Day-1", "Day-2" and so on for the specified date range
I created this automation to keep track of my 60 day preparation window for placements

To use this script, follow these steps:

Set up Google Calendar API:

Go to the Google Cloud Console (https://console.cloud.google.com/).
Create a new project and enable the Google Calendar API.
Create credentials (OAuth client ID) and download the credentials file (JSON format).
Save the downloaded credentials file as credentials.json in the same directory as the Python script.
Install the required Python libraries:

Run pip install google-auth google-auth-oauthlib google-auth-httplib2 google-api-python-client in your command line or terminal.
Update the script:

Replace 'Your_Timezone' in the script with your desired timezone (e.g., 'America/New_York', 'Europe/London', etc.).
Modify the start_date and end_date variables to define your desired date range.
Run the script:

Execute the Python script in your preferred Python environment.
The script will prompt you to authorize access to your Google Calendar account.
Once authorized, it will start adding the events to your Google Calendar one by one.