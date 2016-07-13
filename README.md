# twitControl
Twitter Interface module for MagicMirror<sup>2</sup>

## Dependencies
  * An installation of [MagicMirror<sup>2</sup>](https://github.com/MichMich/MagicMirror)
  * [Twitter Dev Access Tokens](https://dev.twitter.com/oauth/overview/application-owner-access-tokens)
  * `npm install user-stream`

## Installation
 1. Clone this repo into your `modules` directory.
 2. Configure your `config.js` file with your twitter access tokens:
 
```
		{
			module: 'twitControl',
			position: 'top_left',
			config: {
				api_keys: {
					consumer_key: 'YOUR CONSUMER KEY',
					consumer_secret: 'YOUR CONSUMER SECRET',
					access_token_key: 'YOUR ACCESS TOKEN KEY',
					access_token_secret: 'YOUR ACCESS TOKEN SECRET'
				}
			}
		},
```
 
