# Pinax Screencasts

The goal of Pinax Screencasts is to help developers be more productive with the
tools, apps, and techniques we have developed over the years.

## Ideas

Please use the issues in this repo to file your requests for what you'd like
to see produced.

## Style Guide

In order to build a library of screencasts that maintain a consistent level of
quality, here are the current standards and setup.

### Hardware and Software

* AT2020 USB Microphone
* ScreenFlow
* Sketch (there is a [Sketch file](assets/Assets.sketch) in this repo that contains the assets we use)

### Environment Setup

We record at 2560x1440 and export to 1920x1080. We put windows in full screen
resolution, hiding dock and menu.

We bump the font size up to 36 points in editors and terminals.

Browsers zoom to about 175% to 200% depending on the content.

In ScreenFlow we select all audio clips and select "Smooth Volume Levels" as
well as "Remove Background Noise".

### Recording How-To

It is important to remain focused and reduce any distractions (e.g. don't show
setting up a new `pyenv` if the main point of the screencast is something else).

Make some notes about what you want to show.  First record your screen as you
go through everything, just recording your screen, no audio.  I find it helpful
to sort of talk though it as I go to help with pacing.

You will mess up so when that happens, just pause, and do it again.  If you,
think of each step you are talking about as its own segment then you should
probably just rerecord the whole segment unless you know that the cursor won't
jump around when go to cut out the mistakes.

Once you have end to end screen capture, now it's time to record your voice.

Hit record for an audio clip on your mic. Then press place on in ScreenFlow to
watch your video and talk through an explain what you are doing. Don't worry too
much about timing. If what you explain is shorter or longer than what's happening
on the screen, we can slow things down adn speed them up while editing to get
them matching.

You will misspeak, forget what to say, etc.  Just take a breath, gather your
thoughts and try again, all while it's recording.  We'll cut it all out in a
minute.

Now is the fun part.  Go through first and cut out the segments of the video
that are flubs.  Then do the same with the audio.  Now you have a bunch of clips
with gaps.  Start from the beginning and pull clips together as you listen.

If the audio is too long, then slow down part of your screen recording. You
might want to split things so you can lengthen part that is slow so it doesn't
look abnormally slow typing.  If what you say is too fast, it might be just
fine to have a few seconds of dead time while your screen does things, but you
can also speed up your clip so your viewer isn't bored to death waiting for
`npm install` to finish.

When you switch views like going from terminal to browser, cut the start of the
browser clip to where you ready to show something to save the user from seeing
you type in a url and wait for something to load, then back up the clip a half
second or so on top of the previous one and ScreenFlow will provide a dissolve
transition that looks quite nice. Afterall, we don't need to see you tabbing
around to other running apps. Get on with it.

Aim to keep it 2-5 minutes.  Better to have many short to the point videos, than
a few monoliths.

### Resources

Some blog posts and videos on producing great screencasts:

* [Recording a Great Coding Screencast](https://egghead.io/articles/recording-a-great-coding-screencast)
* [Record Badadd Screencasts](https://egghead.io/courses/record-badass-screencasts-for-egghead-io)
* [Creating a Screencast](https://www.youtube.com/watch?v=HJMEiyK7sEc) (video by Kent C. Dodds)

