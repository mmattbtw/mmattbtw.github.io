---
title: AI TTS Donations # the title
description: A Twitch bot that allows Donations to use AI TTS Voices # description
tags:	
    - twitch
    - mmattDonk
  # a list of tags.
startDate: 2021-10-03 # the date the project started, in format YYYY-MM-DD
endDate: "tba"
status: "wip" # status can be: "complete", "wip", "on_hold", or "scrapped"
headerImage: /assets/images/ai_tts.png # header image. please refer to image relative to site root.
---

This is a project that was made specifically for [elpws](https://twitch.tv/elpws){:class="ext other"} . He always wanted the AI TTS voices used on streamers like Forsen and xQc. I wanted to help him out, however I didn't know of any way to use previous AI voices. I didn't want to train a bunch of voices from scratch, so I didn't know what to do for a while.

Until I got a whisper from [Tajj](https://twitch.tv/tajj){:class="ext other"} . I didn't konw he whispered me until a couple days later, but as soon as he told me, I went ahead and got to work.

![](/assets/images/tajj_screenshot.png)

This project uses the [Uberduck.ai](https://uberduck.ai) API, which basically makes it so that we can use thousands of previously made voices that were trained by the community. There are some pros, and of course, some cons.

### Pros:
* Thousands of previously made voices
* Voice training off the PC (no lag for streamer/training is offsite)
* Easy to use for the streamer+chatter

### Cons:
* Inconsistent amount of wait times.
	* Sometimes the TTS request takes a long time for the request to finish, however sometimes they happen instantly

* Request failures sometimes
	* This isn't that much of a fail, since we are (or have) implemented a way to circumvent this by just trying the request again. (However, again, this increases waiting times)


![](/assets/images/ai_tts.png)

Like some of my other projects, this one is still in heavy development, so stay tuned to the [GitHub Repo](https://github.com/mmattDonk/ai-tts-donations){:class="ext github"} and the [Discord Server](https://discord.gg/mvVePs2Hs2){:class="ext other"}.
