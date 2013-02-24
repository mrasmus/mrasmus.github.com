---
layout: post
title: "UbiCondo: Project Overview"
description: ""
category: UbiCondo
tags: []
---
{% include JB/setup %}

UbiCondo is a project that started as a group effort for a course at UCSD (CSE
118: Ubiquitous Computing); we were provided with Microsoft Kinect for Windows
sensors (basically similar to the Kinect units sold for motion gaming for Xbox
360, albeit with a "near mode" that allows them to be effective at short
ranges) and given the freedom to do effectively whatever we wanted with them.
The idea we came up with was a mix of home automation and inter-computer
coordination, all held together and driven by spatially-aware gesture control.

### What is UbiCondo?

UbiCondo is a hodgepodge of different ideas rolled into one project. Using two
Kinect sensors, a central server tracks users as they move between multiple
rooms in an environment. It enables a mix of interactions classified as
"active" (requiring direct triggering by a user using a gesture) and "passive"
(triggered by user state information, generally positional data within the
 environment). The core purpose of the project is more the framework than any
individual action; there's a lot of potential in motion controlling devices in
an environment, and we wanted to see where such a technology could take us.

Mostly a proof of concept, the first version of UbiCondo has a series of device
interactions: computers can be commanded through motion gestures to "share
activities" (read: transmit browser tabs between instances of Chrome on
different machines), lights can be commanded to toggle on and off (though the
lights will also passively "follow" the user as they move from room to room),
and a zone audio system can selectively mute zones that the user does not
reside in.
