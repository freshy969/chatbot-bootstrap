# 🤖 Chatbot-Bootstrap 🤖


## What is it?

A Chatbot Bootsrap-Kit based on [Meteor](https://github.com/meteor/meteor) and [MongoDB](https://www.mongodb.com). 
We have seen a lot of platforms for chatbots, but what about if you just want your bot running on your website?
This is exactly what this project is for.
It's a simple web-project which is pretty easy to get it up and running. It currently offers API interfaces for API.ai and motion.ai. 
In addition it has a built in tracking view where you can see all recent conversations.

![bot conversation](conversation.png)

---

## Table of Contents

- [What is it?](#what-is-it)
- [Getting started](#getting-started)
- [Contributing](#contributing)

---


##Getting started

1. Add NLP API-keys to the `settings.json` file 
2. Customize your dialog with buttons, avatar or other styling
3. `meteor --settings settings.json`
4. go to `localhost:3000` and start chatting :)

### NLP Engines
To make a chatbot work you need to connect to a NLP Engine. I highly recommend the usage of API.ai:
- API.ai tutorial: https://docs.api.ai/docs/profile-bot-example-agent

### Input Templates
By default the text input is enabled. You can customize the input template according to your needs.
- Type 'show buttons' to see how the button input template looks like.
- Check for the api.ai intent name if you would like to display your buttons only for certain intents.

![buttons](buttons.png)


### Tracking View

The built in tracking view offers a nice way to track all the conversations with the bot.
just go to `localhost:3000/tracking`

![tracking view](tracking.png)


### Deployment on heroku

To deploy your bot on heroku I suggest using the [Meteor Buildpack Horse](https://github.com/AdmitHub/meteor-buildpack-horse)

##Contributing

Please fork this repository and contribute back using pull requests.

Any contributions are welcomed and appreciated.

I hope this helps you in building your next chatbot.


Follow me here on Github or on Twitter [@adrian_krebs](https://twitter.com/krebs_adrian) to stay up-to-date.
