=== Twitter Blockquotes ===
Contributors: kovshenin
Author URI: http://kovshenin.com
Plugin URL: http://theme.fm/plugins/twitter-blockquotes/
Requires at Least: 3.0
Tested Up To: 3.2.1
Tags: twitter, embed, tweet
Stable tag: 1.0

Embed tweets in your posts and pages just like you would a YouTube video -- just copy and paste the tweet URL on a separate line.

== Description ==

The plugin works out of the box. It creates blockquote elements out of your links to tweets with the cite element containing the tweet author. Tweets are cached for better performance.

The plugin itself has got a custom CSS field where you can style your twitter blockquotes however you like. Use the `blockquote.tweet` CSS selector and add an image with some padding on the left, or perhaps style the tweet author differently. Hardcore theme and plugin developers can take advantage of the many filters inside the plugin to make Twitter Blockquotes do whatever they like -- add the author avatars, time and date, action intents and more. Code is well commented and easy to understand.

== Frequently Asked Questions ==

= Can I add author avatars? =

Yes, if you're comfortable with PHP and WordPress' Filters API. Read throughout the source code of this plugin and spot the calls to `apply_filters`. That's where you have to hook in to add avatars, time and dates, reply, retweet and favorite actions and more.

== Changelog ==

= 1.0 =
* First release.
