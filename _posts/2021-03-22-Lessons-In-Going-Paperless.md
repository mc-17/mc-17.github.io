---
layout: post
title: Lessons in going paperless
---

Partially [inspired](https://writings.stephenwolfram.com/2019/02/seeking-the-productive-life-some-details-of-my-personal-infrastructure/) inspired by Stephen Wolfram, a couple of years ago I set off on a mission to get rid of all the paper I own. It's all too easy to paper on paper, but for various reasons, it's pretty dumb.


Firstly - where are your backups? The act of becoming paperless includes making digital copies of your paper records, at which point there's little reason to keep paperwork. There are *some* things (certificates, legal docs) that might be worth keeping, but that's an extremely small section of overall paper shit. Then there's the mental cost - I've probably hesitated and delayed actually sorting some stuff out, and these things are able to hide amongst the genuine rubbish.


## The choices

### Windows

For Windows, there's a clear winner - the [Not Another PDF Scanner app](https://www.naps2.com/) is a small, portable executable that interfaces with the Windows Scanner API to easily scan and combine documents into PDFs, JPEGs, and a couple other formats. After hundreds of documents, it has yet to crash and I don't get the icky feeling all my data is being sent to strangers (well, no more than the baseline of running Windows at all)


### MacOS

MacOS's preview app supports scanning, including via your iOS devices. To do this, Bluetooth must be turned on and devices on the same iCloud account. In general, however, it's a bit of a shitty experience. Preview seems to crash fairly regularly, although works fine for the first half dozen documents in order to maximise the damage of crashes. If you're an Apple guy, then perhaps use...

### iOS

iOS has a nice, hidden feature in the Notes app which supports scanning documents. The scanning process works with the same user interface as the one when scanning via the Preview app on macOS, however is far less buggy (presumably the crashes originate in the implementation of the cluster-fuck which is Bluetooth).

In general it hasn't crashed for me, and Notes does a good job of bundling together sequential scans into documents. As you can store multiple documents in a single note, there's little UI fiddling between scans.

The only downside to the iOS experience is the page detection - sometimes the most subtle of ridges or creases in a piece of paper are enough to send the paper detection into a frenzy, wherein the scanner decides that you're actually trying to scan some odd trapezoidal pieceof paper. Most of the time the app is smart enough to prompt you for a manual crop, but occasionally it's confident that you're scanning oddly-shaped pages and immediately saves it. That and the lack of windowing on iOS means it can be jarring sometimes switching between the Files and Notes app when checking your scans.


## TL;DR

Do it, get rid of your stuff, live a happier life. Don't bother trying to do it directly to a MacBook and use either a Windows machine or iOS device instead.

