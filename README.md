## Back-end Developer Test

### Devcenter Backend Developer Test I

The purpose of this test is not only to quickly gauge an applicant's abilities with writing codes, but also their approach to development.

Applicants may use whatever language they want to achieve the outcome.

## Task

Build a bot that extracts the following from people’s Twitter bio (on public/open accounts), into a Google spreadsheet:

* Twitter profile name
* Number of followers

Target accounts using either of these criteria:
* Based on hashtags used
* Based on number of followers; Between 1,000 - 50,000

The bot is suppose to maintain a session and continously listen to the predefined hashtag

## Development language
* Python 3.6.2

## Getting Started
* You need to set up the following to run the application successfully.

## Twitter Account/App Setup
1. Create a Twitter account in case you don't have one. https://twitter.com/signup
2. Go to apps.twitter.com and click on 'Create New App ' button.
3. Fill out the details of the form correctly.
4. Then click on the ‘Create your Twitter application’ button.
5. Replace the consumer key, consumer secret, access token and access token secret values with the ones you generate.

## Google Spreadsheet
1. Go to the Google API Console
2. Create a new project
3. Click Enable API. Search for and enable the Google Drive API.
4. Create credentials for a service account to access Application data.
5. Obtain OAuth2 credentials from Google Developers Console for google spreadsheet api and drive api
6. Save the file as client_secret.json in same directory as project.
5. Look up this link https://pygsheets.readthedocs.io/en/latest/authorizing.html for more information on Authorizing pygsheets

## Other Information
* Ensure you install all project dependencies
```
pip install -r requirements.txt
```
* Run Test
```
python -m unittest tests.test_bot tests.test_spreadsheets
```

* Run application
```
python bot.py
```

## How to complete the task

1. Fork this repository into your own public repo.

2. Complete the project and commit your work. Send the URL of your own repository to @seun on the Slack here bit.ly/dcs-slack.

## Show your working

If you choose to use build tools to compile your CSS and Javascript (such as SASS of Coffescript) please include the original files as well. You may update this README file outlining the details of what tools you have used.

## Clean code

This fictitious project is part of a larger plan to reuse templates for multiple properties. When authoring your CSS ensure that it is easy for another developer to find and change things such as fonts and colours.


## Good luck!

We look forward to seeing what you can do. Remember, although it is a test, there are no specific right or wrong answers that we are looking for - just do the job as best you can. Any questions - create an issue in the panel on the right (requires a Github account).


## Demo
![screen shot](https://user-images.githubusercontent.com/8668661/33088863-330b4250-ceef-11e7-9e9c-b4fd9ca299d8.gif)
