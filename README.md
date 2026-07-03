# TapLock

TapLock is a website I built for my iOS app, also called TapLock. The whole idea behind the app is pretty simple: you tap an NFC card and it locks the distracting apps on your phone. No fiddling around in a settings menu every time you want to focus, no five step process, just tap the card and you're locked in. When you're done, you tap it again and you're back to normal.

I made this whole thing, the website, the app, and everything else, by myself. I'm Aahish, and this is one of my projects that started as a way to actually fix a problem I kept running into (opening Instagram for "two minutes" and looking up forty minutes later). This repo is just the landing page and marketing site for the app, not the app itself, but I figured I'd put it out there since I built it from scratch with plain HTML and CSS and I'm kind of proud of how it turned out. This was my first project in HTML and CSS actually, I was honestly learning along the way, so some features might not work.

## What's actually in here

This is a super lightweight site. No React, no build tools, no npm install, none of that. Just three HTML files with all their CSS written straight into the head of each page. You could open index.html in a browser right now and the whole thing would just work.

- **index.html** - the main landing page. This is where most of the info about TapLock lives, how it works, why it's different from other screen time apps, who it's for, some FAQs, all that.
- **download.html** - the page that actually sends people to the App Store, plus a little screenshot gallery so people can see the app before they download it.
- **contact.html** - a support page with my email, a template people can use if they're not sure what to write, and answers to some common questions.

There's also a screenshots folder with the actual app screenshots that show up in the download page gallery.

## About the app itself

TapLock uses NFC to control your screen time, which is honestly the part I like most about it. A lot of focus apps let you just tap a button on your own phone to turn the block off whenever you feel like it, which kind of defeats the purpose if you have zero self control at 1am like me. Having to physically tap a card makes the whole thing feel a little more real and a little harder to talk yourself out of.

Here's roughly how it works:

1. You pick which apps distract you the most (social media, games, whatever it is for you)
2. You tap your NFC card and TapLock locks those apps
3. You tap it again when you're done and everything goes back to normal

It's built for students trying to actually study, people trying to build things without getting sucked into their phone every ten minutes, or honestly anyone who just wants a simpler way to stop opening the same three apps over and over.

TapLock is free to download and it's live on the App Store right now. You do need an iPhone with NFC and an actual TapLock card to use it though, since that's the whole point of the app.

## Design stuff

Since this is technically an HTML and CSS project, figured I'd mention the design choices. It's a dark theme, mostly black background with a blue accent color, using the Space Grotesk font from Google Fonts. I tried to keep it clean and not too cluttered since that's kind of the whole philosophy behind TapLock too, less mess, less distraction. Everything is responsive so it should look decent on both a phone and a desktop screen.

## Open source

This project is open source, so feel free to poke around, use it, learn from it, or straight up steal parts of it if that's helpful to you. It's a pretty beginner friendly codebase since it's just HTML and CSS with no frameworks getting in the way, so if you're newer to web dev this might actually be a decent one to read through and see how a real landing page gets put together.

If you end up using any of this for your own stuff, a shoutout would be cool but honestly not required.

## Contact

Got a question, found a bug, or just want to say something about the site or the app? Email me at aahish.abbani@icloud.com. I actually read these.
