# HackerNews Jobs Twitter Integration

[![CircleCI](https://circleci.com/gh/crazybusycom/hackernews-jobs-twitter.svg?style=svg)](https://circleci.com/gh/crazybusycom/hackernews-jobs-twitter)

A simple Firebase listener in node.js to get the new job posts from HackerNews and then to publish them on the *non-official*  [@hackernewsjobs](https://twitter.com/hackernewsjobs) channel on Twitter.

This project was started as a learning experience and I welcome anyone else in the web development community to play with it :smiley: or improve it  :rocket:

## Installation

Set the environment variables by creating the `.env` for `development` and using your deployment capabilities for adding environment variables in `production`:

See https://apps.twitter.com/ to create an application.

| Environment Variable |
| --- |
| TWITTER_CONSUMER_KEY |
| TWITTER_CONSUMER_SECRET |
| TWITTER_ACCESS_TOKEN_KEY |
| TWITTER_ACCESS_TOKEN_SECRET |

Run `npm run dev` for a `development` server.

Run `npm run start` for a `production` server.

## Deployment

In both cases, you should increment the package version using `npm version patch`

### Local

Set the `eb` command and `npm run deploy`

### CircleCI

CircleCI will automatically deploy the latest `master` branch

---

## Credits

Credit where credit is due:
* [HackerNews API](https://github.com/HackerNews/API)
* [HackerNews Jobs](https://news.ycombinator.com/jobs)
