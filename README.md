# tweet-delete
My script for deleting and unfavoriting tweets over 10 days old. Requires a separate credentials.py file with consumer_key, consumer_secret, access_token, and access_token_secret from Twitter.

There is also a Dockerfile and requirements.txt to build a docker image.

```
docker build —tag=tweet-delete .
```
