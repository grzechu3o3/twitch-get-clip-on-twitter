# twitch-get-clip-on-twitter
This app uses Twitter and Twitch APIs to publish selected twitch clip as tweet every day at 17:00.
# All dependencies you need are:
- twit
- node-schedule
- axios

> Note you also need to have Elevated access to Twitter's API as it uses standard API 1.1 <br />
> config.json should contain codes from the twitter developer portal (you need to activate OAuth 1.0a first) and twitch client_id, client_secret and bearer_token that can be generated with gettoken.js (for now you need to put it manually into config)
