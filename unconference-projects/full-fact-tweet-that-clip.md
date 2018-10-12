# Full Fact - tweet that clip

**TL;DR:** Tweets out a small clip of a show \(e.g. Prime Ministers Questions\) during live factchecking. The media/clip is of the person who makes a claim that is then being checked in the text of the tweet.

...you can now see the clip of the moment they said the claim, ready to be tweeted out. After you press the tweet button it automatically tweets out the clip.

{% embed url="https://youtu.be/ExzTgsPDEH8" %}



## **Why is this helpful?** 

Full Fact live factchecks Prime Ministers Questions and BBC Question Time on Twitter. Members of the team tweet out factchecks of the statements politicians and guests make.

If we can add small clips of the politicians or guests actually _making_ the statements we believe the experience for the public would be much nicer!

## **Before**

The sentences are matched to Full Fact's previous factchecks

![](../.gitbook/assets/screen-shot-2018-09-19-at-15.53.29.png)

and when you click the Twitter button it takes you to a draft tweet with just the link of the factcheck in:

![Example draft tweet window, with just a link](../.gitbook/assets/screen-shot-2018-09-19-at-15.54.53.png)

In the real world the final output looks like this

![https://twitter.com/FullFact/status/1039834235232821249](../.gitbook/assets/screen-shot-2018-09-19-at-15.37.23.png)

## **After**

Everything is a little broken, and the sentences are a bit weird, _but_ you can now see a preview of a video inline. 

![](../.gitbook/assets/screen-shot-2018-09-19-at-15.50.44.png)

And when you click tweet...

{% embed url="https://twitter.com/pietropassarell/status/1042435448398864384" %}

**Slides:** [https://docs.google.com/presentation/d/1uEjC8hpJGVkvXLH4i9\_tmwPHON77UrrS4nzTKLth46U/edit\#slide=id.g42107b0f4e\_0\_59](https://docs.google.com/presentation/d/1uEjC8hpJGVkvXLH4i9_tmwPHON77UrrS4nzTKLth46U/edit#slide=id.g42107b0f4e_0_59) 



## Github

Node module to tweet to clip + text status

{% embed url="https://github.com/pietrop/tweet-that-clip" %}

Example server micro-service 

{% embed url="https://github.com/pietrop/tweet-that-clip-server" %}

## Next up 

Look into tweeting as draft  


Post end point

```text
POST 
http://ads-api.twitter.com/4/accounts/18ce54d4x5t/tweet?text=hello,+world&as_user_id=756201191646691328&trim_user=true  

```

Draft end point

```text
POST 
https://ads-api.twitter.com/4/accounts/18ce54d4x5t/draft_tweets?as_user_id=756201191646691328&text=Just+setting+up+my+Twitter
```

### Other improvements

* [ ] Creating a draft tweet with the ability to add text
* [ ] Custom controls for the HTML5 video player, to hone in on the right timestamps
* [ ] Sort out the video pipeline
* [ ] Add subtitles/closed captions directly onto the video
* [ ] Configure it to the Full Fact account

\*\*\*\*

## **Team**

* Mevan Babakar, Full Fact 
* Simon Coltman, Full Fact 
* James Dooley, BBC News Labs
* Dave Bevan, BBC News Labs
* Pietro Passarelli, BBC News Labs

