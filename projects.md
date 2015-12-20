---
layout: page
title: Projects
permalink: /projects/
---

Years: [2015](#2015) (2), [2014](#2014) (7), [2013](#2013) (1), [2012](#2012) (1)

<a name="2015"></a>
## 2015 [&#94;](#top)

<a name="humanizeher"></a>
### Humanize Her (for Comedy Hack Day LA 2015)

I went down to LA for another Comedy Hack Day and [my team created "Huamize Her"](http://www.comedyhackday.org/demosmade/2015/8/27/humanize-her) which is an app that you can point at a woman to make her look like a man so you can focus on what she's saying. We made the finals, which was great, but the projector died on us for the big show, and that was not so great.

The app started out that weekend as a web app, specifically an Android web app since iOS didn't include the camera APIs we needed in Safari, but I made it in to a native iOS app after I got back from LA...because...I have a sickness. Here's [a demo of the completed iOS version](https://www.youtube.com/watch?v=ekbgMfyBQqQ), and here's [the repo](https://github.com/mikeflynn/humanize-her-ios).

<a name="alexa"></a>
### Amazon Alexa Skills - Various apps to add functionality to Amazon Echo

I got an Amazon echo for the same reason everyone did: I want JARVIS! I've been making a few apps to get a little closer to that eventual "Everyone is Iron Man" future.

...starting with a way to play [Jeopardy](/2015/07/14/amazon-alexa-jeopardy/), of course.

<a name="eggjs"></a>
### Egg.js - A Simple Way to Add Easter Eggs to Your Site

I always add easter eggs (little secret features) to nearly everything I write, but that's especially true on web pages (try typing "abby" on [Punching Kitty.com](http://punchingkitty.com)). Finally I got tired to reimplementing the same easter egg code and created a small library in pure Javascript: [Egg.js](http://thatmikeflynn.com/egg.js/)

Egg.js was submitted to [Hacker News](https://news.ycombinator.com/item?id=9415784) and it quickly made the home page. The [repo on GitHub](https://github.com/mikeflynn/egg.js) now has over 1000 stars and counting!

<a name="quackerjack"></a>
### Quackerjack - A YouTube Comment Analyzer

A command line application (or web service) that takes a YouTube video link and returns various data points about the comments: Avg per day, total comments, top keywords and sentiment analysis.

[github.com/mikeflynn/quackerjack](https://github.com/mikeflynn/quackerjack)

<a name="screenshop"></a>
### Screenshop (for Comedy Hack Day SF 2015)

<iframe width="560" height="315" src="//www.youtube.com/embed/VQQIodnt53g?rel=0" frameborder="0" allowfullscreen></iframe>

Runner Up at Comedy Hack Day SF 2015! We created an app that will fix the low battery indicator in your iPhone screenshots...and a few other things.

We've yet to release the app to the public, though it was fully functional outside of the last feature which was more of a joke at the time. However, after the show I made a web service, written in Go, that can turn that last feature in the demo [in to a reality](https://github.com/mikeflynn/chd7-screenshop-server).

<a name="2014"></a>
## 2014 [&#94;](#top)

<a name="whoopee"></a>
### Remote Whoopee Cushion

<iframe width="560" height="315" src="//www.youtube.com/embed/q_yuuID4ET8?rel=0" frameborder="0" allowfullscreen></iframe>

An Android whoopee cushion app that gives users the best designed and largest feature set of any of the existing such apps on the Google Play store.

Features:

* Remotely fire the fart via your Android Wear watch.
* Record your victims' reactions!
* Record custom noises to trigger or use any of the great built-in options.
* Set an optional delay for additional surprise.

Available now for $0.99 on the Google Play store: [Remote Whoopee Cushion](https://play.google.com/store/apps/details?id=io.github.mikeflynn.remotewhoopeecushion)

<a name="gmail"></a>
### Gmail-clj

![placeholder](/public/images/gmail-clj.jpg "Medium example image")

A Clojure library that allows for the easy interfacing with the [new GMail API](https://www.youtube.com/watch?v=UhdiQmS3kDs). Available via [Clojars](https://clojars.org/gmail-clj) or the [GitHub project page](https://github.com/mikeflynn/gmail-clj).

<a name="convo"></a>
### Conversations Plus

![placeholder](/public/images/coolio.jpg "Medium example image")

Ever been jealous of news broadcasters who have the benefit of having a picture of whatever their talking displayed behind them? Well don't be! Just fire up Conversations Plus, add in a few of your favorite keywords to look for and start gabbing. Conversations Plus is a web app that monitors what you or anyone else in microphone range is saying and displays images (or sounds, or gifs!) on the screen.

Try it out: [mikeflynn.github.io/conversations-plus](https://mikeflynn.github.io/conversations-plus/)

<a name="stltoday"></a>
### STLToday Paywall Buster

![placeholder](/public/images/stltoday.jpg "Medium example image")

The St. Louis Post Dispatch is my hometown newspaper (Go Cardinals!) and when they instituted a weak client-side paywall I took it as a challenge to knock it out so I can continue to read my Cardinal news. It took a 5 minutes.

* [Get the latest release.](https://github.com/mikeflynn/stltoday-paywall-buster/releases/tag/v2.2)
* [Check out the GitHub page.](https://github.com/mikeflynn/stltoday-paywall-buster)
* [Read some press I got about it when I released it via Twitter.](http://blogs.riverfronttimes.com/dailyrft/2014/04/this_guy_hacked_the_st_louis_p.php)


<a name="beatsclj"></a>
### Beats-clj

![placeholder](/public/images/beats-clj.jpg "Medium example image")

A Clojure library that allows for easy use of the [Beats Music API](https://developer.beatsmusic.com/docs).

Available on [Clojars](https://clojars.org/beats-clj) and on the [GitHub project page](https://github.com/mikeflynn/beats-clj).

<a name="sentence"></a>
### Beats Music: Sentence to Playlist

![placeholder](/public/images/sentence.jpg "Medium example image")

A web application, optimized for mobile, that allows the user to sign in using their Beats Music account and save the "Sentence" function as a playlist that can be downloaded and played offline.

Use it here (requires Beats Music subscription): [sentencesaver.theangrytruth.com](http://sentencesaver.theangrytruth.com)


<a name="beatschrome"></a>
### Beats Music Chrome App

![placeholder](/public/images/chromebeats.jpg "Medium example image")

Since there is no Mac application for Beats Music, I created a simple Google Chrome application wrapper to the [Beats Music.com](http://www.beatsmusic.com/) web interface. *The app now has over 27,000 weekly users.*

Available in the Google Chrome App Store here: [Beats Music Chrome App](https://chrome.google.com/webstore/detail/beats-music-chrome-app/hjeiboeolldhkhfldcipahpigbebkioo)

<a name="2013"></a>
## 2013 [&#94;](#top)

<a name="punchingkitty"></a>
### Punching Kitty

![placeholder](/public/images/punchingkitty.jpg "Medium example image")

From 2009 to 2013 I wrote [an award winning humor site](http://punchingkitty.com/about) about St. Louis news (where I lived at the time). Punching Kitty was a writing project for the city of St. Louis to have a little fun and try to get everyone to stop taking themselves so seriously...and hopefully highlight some critical issues along the way.

The complete archives are still online: [Punching Kitty.com](http://punchingkitty.com/)

<a name="2012"></a>
## 2012 [&#94;](#top)

<a name="keyword"></a>
### Chrome Keyword Search Extension

A Chrome Extension that allows the user to automatically search on a loaded webpage for a set list of keywords. Great for identifying an article for specific keywords for ad placement.

Available on [the GitHub product page](https://github.com/mikeflynn/chrome-keyword-search).
