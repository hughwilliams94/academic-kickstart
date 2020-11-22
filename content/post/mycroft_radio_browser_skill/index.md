---
title: "A Radio Skill for Mycroft"
author: ["admin"]
date: 2020-07-15T12:47:00+01:00
categories: ["mycroft", "MSc"]
draft: false
summary: "Creating a Mycroft skill that finds radio streams"
---

As part of the learning process for my MSc project, I have set up a Raspberry Pi running Mycroft in my bedroom. This will partly be useful for debugging skills that I design for the lab assistant, but was also just a fun learning exercise. Anyways, I got it all set up fine and managed to get various functionality going (alarms, timers, Spotify); however, I found that there was no radio functionality (either built-in or in the Mycroft marketplace). Therefore, I set about trying to implement a simple skill of my own.

The skill, which is available on [Github](https://github.com/hughwilliams94/radio-browser-skill), uses the [pyradios](https://github.com/andreztz/pyradios) wrapper for the radio-browser.info [API](https://api.radio-browser.info/) and the Common Play Framework implemented in Mycroft Core. It is pretty rudimentary currently, users can either ask for a specific station, for example, "Play BBC Radio 4", or a genre of radio station.

In the future I hope to implement some functionality to flesh out the skill (I have since found various other implementations that I will use for inspiration). I also want to try out using the Behave integration testing setup that the Mycroft team have written as preparation for my project.
