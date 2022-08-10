# Dweeber < / slash commands>

✅ This branch is actively maintained and updated

**Please consider putting a ⭐ on this repo. It helps!!**

![](readmefiles/dweeber-half.jpg)

# Status

![](https://img.shields.io/github/issues/dchu096/dweeber) | ![](https://img.shields.io/github/forks/dchu096/dweeber) | ![](https://img.shields.io/github/stars/dchu096/dweeber) | ![](https://img.shields.io/github/license/dchu096/dweeber) 

![Discord Banner 2](https://discordapp.com/api/guilds/958317326585987112/widget.png?style=banner2)


# About Dweeber


Dweeber is a discord bot built with features in mind, helping you build, moderate, entertain your server.

The main features of this bot:


> Detailed Moderation: We included detailed moderation system for you to bring to your server. Not just a kick and ban like some discord bot but a full warning system [WIP]



> Advanced Entertaining: Dweeber are packed with advanced music features including the most basic play, pause, skip command and more advanced volume and a non-laggy music experience into your server for absolutely no cost



> Easy Dashboard: Dweeber will be provided with a useable, decent-looking dashboard to manage/view your current queue. [WIP]



> Mini Games: To help engaging your server member dweeber is also packed with some mini-games such as Would you Rather and guess the number.



> Economy: Dweeber has an economy system to also maintain your server's engagement rate. [WIP]


Bot informations:

invite: https://discord.com/api/oauth2/authorize?client_id=984042951107821648&permissions=1532228922615&redirect_uri=https%3A%2F%2Fpanel.dweeber.dev%3A8443%2Fcallback&scope=bot%20applications.commands

Permission: 1532228922615

Bot library: discord.js v13

# Credits

Thankyou for [@behold](https://github.com/BeholdIsLost), [@mira](https://github.com/MiraBellierr) for helping out with the bot bugs

Dashboard are forked and edited from [@Tomato](https://github.com/Tomato6966)

API used:

https://ipstack.com/

https://apilayer.com/marketplace/image_to_text-api#:~:text=Recognizes%20and%20reads%20the%20text%20embedded%20in%20images.&text=Image%20to%20Text%20API%20uses,both%20handwriting%20and%20printed%20materials.

https://apilayer.com/marketplace/whois-api

https://www.weatherapi.com/

https://api.nasa.gov/

https://tracker.gg/developers

# Self-hosting??

If you would like to self host this bot please following the following instructions:

# Download this code 

# Delete folder "Readme files"

# Open config.json and edit the details

```

{
    "TOKEN": "", // Your bot token, obtain it from https://discord.com/developers/applications
    "OwnerID": "", // Your ID. open dev option and copy your ID on discord
    "NASAAPI": "", // API for NASA, obtain from https://api.nasa.gov/
    "TRACKERAPI": "", // API for tracker Network, obtain from https://tracker.gg/developers
    "WeatherAPI": "", // API for weather command, obtain from https://www.weatherapi.com/
    "SRAAPI": "", // API for images, some should be optional but strongly recommended. get from https://some-random-api.ml/. Free version will have a watermark tho.
    "musicAPI": "", // Lyrics API, obtain from https://developer.musixmatch.com/
    "FORTNITEAPI": "", // Same as trackerAPI.
    "SERPAPI": "", //Play store search API. get from https://serpapi.com/
    "OPENAIKEY": "", //OpenAI key. get from https://openai.com/api/
    "youtubeCookie": "", // Optional but if you want just look up guides on google
    "spotify_api": {
        "enabled": true, // Please leave it true if you want able to fetch songs from spotify and play it
        "clientSecret": "", // https://developer.spotify.com/
        "clientId": "" // https://developer.spotify.com/
  },
    "MONGOURL": "" // Your mongo connection sting. https://www.mongodb.com/
}
```

# Open terminal and do `npm install` or `yarn install`

# Run the bot by doing node shard.js

