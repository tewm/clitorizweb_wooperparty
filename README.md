# clitorizweb_wooperparty
Wooper Party CSS code for clitoriz.cf profiles.

[Video demo](https://cdn.discordapp.com/attachments/226918197872427008/900792196662460536/dQ6J4hLrH5.mp4)

[Demo link](http://web.archive.org/web/20211206000339/http://www.clitoriz.cf/profile.php?user=tom)

# How to use
Just copy and paste the code into the "css" field in your settings, obviously. There are however some things to consider:

* As far as I know, I'm not able to change the alert-banner's text due to the way ClitorizWeb's HTML was built, so [the text in the middle will always default to whatever it currently says](https://i.imgur.com/lJb65wo.png).
* Your profile picture won't spin if your profile has the new header due to code changes between the old and new headers. This can easily be resolved by toggling "old header" on or changing ``.pfp{`` (line 62) to ``#profile-picture{``.
