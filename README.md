<center><h1> 🗓️ Schedule-Tweet</h1>
[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)
<h3>Schedule tweet and thread using github action 🚀🚀🚀</h3></center>
<hr>

## Introduction
Schedule tweet and thread as many as you want. This script will check if schedule time is already past. if yes, it will post that tweet/threat and will delete it from tweet.json file. If any image is used that image also will be deleted automatically from images folder. (images folder should always have at least 1 photo or folder will be deleted automatically.)

## Usage

- Fork this repo.
- Get a twitter developer account and create an app.
- Go to repo settings > Secrets > Actions.
- Save the API key as TWITTER_CONSUMER_KEY
- Save the API secret as TWITTER_CONSUMER_SECRET_KEY
- Save the access token as TWITTER_ACCESS_TOKEN
- Save the access token secret as TWITTER_ACCESS_TOKEN_SECRET

- Edit tweet.json.
	- Check sample_tweet_and_thread.json for learning how to format.
	- Either text or image can be omitted for any post as exemplified in sample_tweet_and_thread.json.
	- Line breaks can be inserted in the tweet with the escape sequeence \n.
- Now, your tweeting workflow is ready. You can manually trigger it...
- Or set a run schedule for it to follow.
	- Go to line 8 and 9 of .github/workflows/main.yml. Delete the # symbol at the start of the line and set your run frequency of choice.

#### Give a Star ⭐ it helps you.

## Contributing

Contributions are always welcome!
