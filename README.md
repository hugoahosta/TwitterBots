# TwitterBots
Increase your Twitter presence with these bots.

Currently, three bots which will expand your social media (Twitter in these case) outreach by maintaining activity level.

-----
> bot **Statusio** - Based on a week of the day, picks the topic and scraps top articles from the leading webpages of to post tweet them as a status with a comment and relevant hashtags.

> bot **Folowero** - Follows back whoever follows you.

> bot **Activius** - Given the keywords searches for the tweets, likes them, if not liked before, retweets them if not. retweeted before.

------
Run the `.py` file in a terminal and bot gets to work:

![terminal](https://media1.giphy.com/media/f94ATwIosgMFG5xwjs/giphy.gif)
![tweeter](https://media0.giphy.com/media/gLbiraGzJQFuPN0WOH/giphy.gif)

## Folders Structure
```
TwitterBots/
   |
   |———bots/
   |    |——— activius.py
   |    |——— cfg.py
   |    |——— dayandtime.py
   |    |——— followero.py
   |    |——— statusio.py
   |
   |——— .gitignore
   |——— LICENSE.txt
   |——— README.md
   |——— requirements.txt
```

## Installation

Currently, the only option is to fork the repo and run it through your terminal by executing each of the bots individually.
Before executing python file you need to register as a developer on a Twitter API and then make sure you set up your Tweeter API credentials through the terminal.

#### Linux $ OS X:
```
export CONSUMER_KEY="your_consumer_key"
export CONSUMER_SECRET="your_consumer_secret"
export ACCESS_TOKEN="your_access_token"
export ACCESS_TOKEN_SECRET="your_access_token_secret"
```

After you have exported your Twitter credentials you can execute files through the terminal.
```
python3 bots/statusio.py
```

_P.S. For the version 0.5.0 bots will be deployed using Docker container and the guide will be added to this repo_

## Release History

* 0.0.1
  * Work in the process..


## Development Setup

A list of the dependencies is available in the `requirements.txt` file. The majority of packages are included with a standard python 3.5+ install.

## Meta

**Follow me on social media:**

[![Bexx Modd GitHub](https://i.imgur.com/rnEivsV.png)](https://github.com/bexxmodd) [![Bexx Modd Twitter](https://i.imgur.com/BMdn8gX.png)](https://twitter.com/bexxmodd) [![Bexx Modd LinkedIn](https://i.imgur.com/NxflDxM.png)](https://www.linkedin.com/in/bmodebadze/)

---------
Distributed under the **MIT** license. See `LICENSE.txt` for more information.
