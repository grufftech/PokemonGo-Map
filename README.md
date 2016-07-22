Very not done yet.  

lots to clean up.  

cobbled together from a bunch of different scripts until I have time to rewrite in a clean way.

# example;

`python slack-notifier.py -a google -u {email} -p {password} -l "30.300067, -97.696347" -st 3`

 - a = auth source. `google` to `ptc`
 - u = username
 - p = password
 - l "Austin" = location coordinates for google.
 - st = steps to travel from start location.  hunt range.

# environment .env file

    SLACK_WEBHOOK_URL={your slack webhook URI}
