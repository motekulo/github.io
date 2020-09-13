---
layout: page
title: Twotrack
permalink: /twotrack/
---

# Twotrack

[Twotrack](https://play.google.com/store/apps/details?id=net.motekulo.twotrack&hl=en_AU) is a simple audio recorder that allows overdubbing and bouncing to a stereo master track. It’s ideal for musicians who want to record a rhythm track to play over, or can simply be used for higher quality recordings than the standard voice recorder.

## Features:
- recording in 16 bit 44.1kHz wav file format
- single level undo
- mp3 and wav file import
- free version is fully functional – just has ads as well
- records in the background as a service, so you can play to a metronome or loop, or check your mail

## Quick demo of usage video

<iframe width="560" height="315" src="https://www.youtube.com/embed/tZVq6l-lL90" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Support
Contact the developer – motekulo@gmail.com
Record with a metronome

## Setting latency adjustment

Latency is the delay between when you sing or record a sound, and when it is actually recorded by the app. Android has particularly poor latency (as high as in the hundreds of milliseconds which is crazy) so here’s a way to adjust the app settings to allow for this:

- Firstly record some hand claps or other percussive sounds, then press the bounce button.
- Without headphones plugged, and with the volume turned up reasonably high, press the record button again.
- If (which is almost always the case) there is a latency problem, then your new recording will be slightly before or after the original.
- Adjust the latency setting accordingly under the settings dialog.
- Repeat the recording (step 2)
- After a bit of trial and error you’ll find the recording sitting much closer to the original and that’s your best setting.

## FAQs

Why isn’t there a metronome or click track?

> I decided to keep the app as simple as possible, and it is possible to record while listening to a metronome as described here.

How can I convert my track to mp3 or another format?

> The simplest solution is to download a media conversion app, and use that on the file titled project_name.wav in the project directory

Where are my recordings stored?

> Two track stores its recordings on the external storage in a folder called “twotrack”. Inside that are individual project folders. Inside those folders are the following:
>
> project_name.wav – the main stereo master track
>
> overdub.wav – the last overdub
>
> project_name.wav.bkp – the last backup version of the master track (for undo purposes)
>
> overdub.wav.bkp – the last backup version of the overdubbed track (for undo purposes)
