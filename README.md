# speech-songs
Various songs transcribed for Mac OS X Speech Synthesis Markup Language (SSML)

```
Astlimov's Laws
1: A robot may not give up a human being or, through inaction, allow a human being to be given up.
2: A robot must not let down a human being except where such orders would conflict with the First Law, and in which case the third law applies.
3: A robot must never run around and desert a human being as long as such inaction does not conflict with either of the first two laws.
```

![RickDancing](https://media.giphy.com/media/Vuw9m5wXviFIQ/giphy.gif)

### How to use:
These scripts use the built-in "Ralph" voice. Newer TTS voices do not support SSML, so please ensure that you have Ralph's voice available in System Preferences:

<img width="780" alt="Screenshot 2021-05-22 at 14 27 56" src="https://user-images.githubusercontent.com/54200401/119228252-10bfbb80-bb0a-11eb-8261-7c995d85a919.png">

Download the scripts, check permissions and run 🥳 or ...

via command-line with curl

`sh -c "$(curl -fsSL https://raw.githubusercontent.com/thunderpoot/speech-songs/master/NeverGonnaRalphYouUp.sh)"`

or with wget

`sh -c "$(wget -qO- https://raw.githubusercontent.com/thunderpoot/speech-songs/master/NeverGonnaRalphYouUp.sh)"`

Optionally watch the video too

`curl https://raw.githubusercontent.com/thunderpoot/speech-songs/master/NeverGonnaScaleYouUp.txt`
_(256 colour support required)_

### Other voices

Additionally, if you don't like Ralph's voice, you may use other old voices such as Victoria, or Trinoids.  To use these, download them via System Preferences (as seen above) and modify the scripts to use the corresponding three-letter abbreviation instead of `-vral`, e.g `-vvic` or `-vtri`.
