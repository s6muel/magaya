---
title: "Magaya Manual"
description: "Start communicating on the Magaya Matrix instance."
lead: "Start communicating on the Magaya Matrix instance."
date: 2020-11-16T13:59:39+01:00
lastmod: 2020-11-16T13:59:39+01:00
draft: false
images: []
menu:
  docs:
    parent: "get-started"
weight: 20
toc: true
---

Before you continue, you should make yourself aware of our [Privacy Policy](/privacy-policy/), [Transparency Report](/transparency/), and [Terms of Use](/terms/) if you haven't already.

## What you'll need

1. A username and password to [make an account](#making-an-account), and [a Matrix client](#choosing-a-matrix-client).
	- That's it! Seriously. ***Everything else is optional***.
2. A second password for account recovery and to [securely back up](#encryption-keys) your encryption keys. (Optional, *Highly Recommended*)
3. An email address to recover your account if it's lost. (Optional, *Recommended*)
	- See our [privacy policy](/privacy-policy/) and [transparency report](/transparency/) to see what we do with your email.
<br></br>
---

💡&nbsp;&nbsp; You can use a password manager like <a href="https://bitwarden.com" target="_blank">Bitwarden</a> or <a href="https://keepassxc.org/" target="_blank">KeePassXC</a> to store and generate your passwords.

---

## Choosing a Matrix client

A Matrix client is a program that works on the <a href="https://matrix.org" target="_blank">Matrix network</a>. A client will allow you to connect to servers such as Magaya.org; to add friends, make video calls, create communities, collaborate with colleagues, start chat rooms, send attachments, and more. Think of a client as an app like WhatsApp, Facebook Messenger, Signal, iMessage or FaceTime.

Matrix clients run on your computer, on your phone, or on any device using a web browser. And the best part? You can communicate to anyone on the Matrix network no matter what client (or homeserver) you decide to use! This means that if your favourite client were to stop development (which is unlikely on the bigger projects), you can still utilise the Matrix network. This is just the beginning of the benefits of [decentralisation](/docs/get-started/spoken-glossary/#decentralisation) and [open source software](/docs/help/faq/#why-open-source-software)!

Move on to our [recommendations](#recommendations) to choose a client to install.

<br></br>

---

🤔&nbsp;&nbsp; Why use Matrix over other apps? Read our [blog](/blog/) to find out.

---

### Recommendations

If you don't want to install any software, we host the [Element](https://element.magaya.org) and [Cinny](https://cinny.magaya.org) web clients that run in your browser (or self-host your own). This gives you the complete freedom to talk around the world without installing any software. Web client users can [skip ahead](#making-an-account).

We recommend that new users stick with <a href="https://element.io/get-started" target="_blank">Element</a>, as it's developed by <a href="https://github.com/vector-im" target="_blank">the team behind Matrix</a>, is fully featured with a clean interface, and works on all platforms.

**Other clients we recommend:**

- <a href="https://element.io/get-started" target="_blank">Element</a>
	- Works on Linux, Mac, Windows, iOS, Android, and in your browser.
- <a href="https://schildi.chat" target="_blank">SchildiChat</a>
	- Works on Linux, Mac, Windows, ~~iOS~~ Android, and in your browser.
	- Provides easy access to new and developmental features.
	- Is a fork of Element.
- <a href="https://fluffychat.im/" target="_blank">FluffyChat</a>
	- Works on Linux, iOS, Android, and in your browser.
	- No native voice or video calling function (has voice messaging).
- <a href="https://cinny.in" target="_blank">Cinny.in</a>
	- Works anywhere!
	- A clean and lightweight browser-based client for Matrix. It's focused on personal messaging, and does not support voice or video calling.
- <a href="https://github.com/poljar/weechat-matrix" target="_blank">Weechat-Matrix</a>
	- A command line only Matrix application written in Python.
	- For the passionate typists.

Once you have downloaded and installed your preferred client, you can move on to [making an account](#making-an-account).
<br></br>

---

💡&nbsp;&nbsp; You can use your account on any client. So don't get too held up on this step!

---

## Making an account

This guide will be specifically for Element, but should apply to most Matrix clients.

1. Open up the Element client.

2. Click `Create an account`

3. Locate "Host account on matrix.org" on your screen. To the right of this, select `edit`, type in this address: `matrix.magaya.org`, and click `Continue`.

	- *By default Element will want to use Matrix.org [homeservers](/docs/get-started/spoken-glossary/#matrix). So to use Magaya's homeserver and enjoy low latency talking in Australia, you need to change it!*
<br></br>
4. Type in your desired user name (for example `magaya`). Then type in a [strong password](/docs/get-started/spoken-glossary/#passwords) in the password field.
	- *We suggest generating a random password and storing it using a password manager. For more information, see our [note on passwords](/docs/get-started/spoken-glossary/#passwords).*
	- *You can [change your display name](#make-it-yours) later, but your user name cannot be changed.*
<br></br>
5. Enter an email address as a way to recover your account if you lose your password.
	- ***Optional,*** *and you can [do this later](#email).*
	- *You should consider using an email anonymising service like <a href="https://anonaddy.com" target="_blank">AnonAddy</a>.*
<br></br>
6. Click `Register`.

	- *If you used an email, check your inbox as you will receive a verification link. Once you have verified your email, return to Element to sign in.*
<br></br>
7. That's it, you're all done and you can sign in with your new account!

	- *We highly recommend that you [set up a recovery method](#security-and-recovery) if you haven't done already.*

Feeling risky and don't want to set up a recovery method? Skip ahead to [personalising your account](#make-it-yours) or just [start chatting](#start-chatting)!

<br></br>

---

🚨&nbsp;&nbsp; If you lose access to your account and you don't have a recovery method set up your account and data will be [gone forever](/docs/help/faq/#gone-forever)!

---



### Security and recovery

This is *the* ***most*** important step in regards to your security and privacy. To find out why this matters, read about [cross signing](/docs/get-started/spoken-glossary/#cross-signing).

We recommend that you take a minute to set up a [back up of your security keys](#encryption-keys) for the purposes of account recovery and [cross signing](/docs/get-started/spoken-glossary/#cross-signing) your sessions. This method provides the best user friendly experience, higher security, and more privacy.

An email address can be used to recover your account. However, if you set up a second password and are confident in your ability to not forget or lose your passwords, you might aswell keep your email private (or use a service like <a href="https://anonaddy.com" target="_blank">AnonAddy</a>)! But don’t forget, lost accounts [are gone forever](/docs/help/faq/#gone-forever)!

#### Encryption Keys

Making a back up of your security keys.

1. Open Settings in Element by clicking on your avatar in the very top left hand corner (by default it's the first letter of your username), and then click `Security & Privacy`.

2. Find `Encryption Secure Back Up` and click `Set Up`.

3. Select the `Enter a security phrase` option and click `Continue`.

4. Type in your security phrase and click `Continue`.

	- *This should be different from your main account password! Make sure to store it somewhere safe in case you need to recover your account or verify a session!*
<br></br>
5. Confirm your security phrase by re-typing it and click `Continue`.

6. Now you're presented with a randomly generated passphrase. You should either:

	- `Download` it in plain text (not recommended *unless you encrypt it*); or
	- `Copy` it and place it in a note with your Magaya login details in your password manager, or write it down and keep it somewhere safe (recommended).
<br></br>

7. Once you have saved your generated passphrase, click `Continue`.

8. You're done!

You can now move on to [personalising you account](#make-it-yours), or [attach an email](#email) to your account if you want to.
<br></br>


---

💡&nbsp;&nbsp; Find out more about [using your security keys](/docs/get-started/spoken-glossary/#cross-signing) for account recovery and cross signing sessions.

---

#### Email

How to attach an email to your account.

1. Open Settings in Element by clicking on your avatar in the very top left hand corner (usually the first letter of your username), and then click `All Settings`.

2. Make sure you are in the `General` tab (located on the left of the settings menu).

3. Scroll down to `Email addressess` and type in your desired email. Then click `Add`.

4. Check your inbox, you will receive an email with a link `Please verify your email`: click it to verify your email.

5. You're done!


### Make it *yours*

Now you have your shiny new account, there's a good chance that you want to personalise it, and make it a bit more... *you*. This is how you do it.

1. Open your Element client, and open `Settings`.

2. You are presented with your `General Settings`, and your Profile should be in front of you.

3. Change your `display name` if you wish (perhaps you'd rather capitalise your username?).

4. Click your Avatar to the right of your display name, and select a photo to upload.

5. You're done!

## Start chatting

If you've gotten this far, you now have a secure, personalised account on Magaya.org and you can start chatting with anyone on the Matrix network. Congratulations!

Here's a couple of spaces and rooms for you to get started:

- [Magayamirr Space](https://matrix.to/#/#Magayamirr:magaya.org) - Home for Magaya and other rooms we recommend!
- [Magaya Live Updates](https://matrix.to/#/#status:magaya.org) - Live updates on Magaya's services to you.
- [Australia](https://matrix.to/#/#australia:magaya.org) - *The* room for Australia. Or check out [the Space](https://matrix.to/#/#australia:matrix.org) for a massive directory! There's a room for every state, *a lot* of cities, and a variety of topics.

### Add a friend

When you create an account, you may have noticed that the Matrix homeserver gives you an address or Matrix ID (MXID). It's very similar to an email address. Let's say your username is 'dave' -- your MXID would be `@dave:magaya.org`. Simple right? Knowing this, let's add your first friend.

Have your friend's MXID at hand. Let's use `@david:magaya.org` for the guide, but if you have a friend's MXID feel free to use that!

1. Open your Element client. On the left is a list with `Home`, `People`, and `Rooms`.

2. Next to `Home`, click the plus symbol `+`, and then `Start a new chat`.

3. Type in or copy paste `@david:magaya.org` into the search bar, and click `Go`.

4. Once your friend accepts your invitation, you will be able to chat together privately and securely!

Remember how we said you can chat with anyone on the Matrix network? This means you can also talk to people that are using different Matrix homeservers. For example, your friend with the username `playwright` might be on the Matrix.org network, you just need to add `@playright:matrix.org` as a friend, and you're away!

### Join or open a room

In rooms you can voice and video call, screen share, and collaborate with tools using the [Dimension integrations manager](/docs/help/faq/#collaborate-with-integrations).

Now that you've added a friend, the process is similar to joining and opening your own rooms. Try and join the `#magaya:magaya.org` room or create a room for yourself! Otherwise, follow these steps:

Did you notice the change to `#` for room addresses, instead of `@` for users?

1. Open your Element client. On the left is a list with `Home`, `People`, and `Rooms`.

2. Next to `Home`, click the `+`, and then `Join public room`.

3. Type in or copy paste `#magaya:magaya.org` into the search bar.

	- *You are also presented with a public list of rooms on the Magaya instance available for you to join!*
<br></br>
4. Click `Join`.

5. You're in! Say hello, or try creating your own room and invite your friends!

	- *If you create a room with encryption, this cannot be changed later. You might want to read our [notes on group calls](#a-note-about-group-calls) to find out why this might matter to you.*
<br></br>

---

💡&nbsp;&nbsp; [Matrix.to](https://matrix.to/) let's you easily share your Matrix ID and rooms. Try it for yourself and share your link around!

---



## Start your own community

[Spaces](/docs/get-started/spoken-glossary/#spaces) within Element allow you to create a home for your different rooms and the people you know. They can be public and open for anyone to join, or private so that your team can collaborate on their next project, or your family can share their photos and easily communicate. Think of Spaces like starting your own Discord server, or using Slack to organise projects with colleagues.

How you organise and grow your community is up to you!

1. Open your Element client. To the far right, under your avatar, is a `+` symbol -- click it!

2. You're given the option of a Public or Private room, choose your preferred option.

	- *Public rooms are good for open communities, and can be joined freely by anyone. Choose the private option for things like team projects, business collaboration, family chats, and so on.*
<br></br>
3. Add a logo, name your space, specify an address if you want to, and write a brief description.

4. Click `Create` and you're presented with your shiny new Space!

If you have an existing room, or you want to create a new one for your space, click `Add` on your Space homepage, or by click the `+` symbol  next to your Space name on the right of your screen.


## A note about group calls

As of writing this on the 23rd of Jan, 2022, Element does not natively support encrypted calling in group chats. Instead, <a href="https://jitsi.org" target="_blank">Jitsi</a> is used to handle encrypted group calling. It's not all bad news though! <a href="https://matrix.org/blog/2021/12/22/the-mega-matrix-holiday-special-2021#native-matrix-videovoip-conferencing" target="_blank">Encrypted voice and video calling will be available in early 2022!</a> This means that if you want to engage in a group video and voice call natively in Element, the room needs to be unencrypted, or you can utilise Jitsi. 

Since we expect to have native support any time now, Magaya is not currently hosting Jitsi. However, if you have a need for this please [let us know!](/contact/)
## Further reading

A congratulations is in order! You now have a basic understanding of using Element and communicating privately using the Magaya Matrix instance!

Armed with that knowledge of *how* to use it, you should now seek to understand *what* you're doing and *why* it matters.

The [Spoken Glossary](/docs/get-started/spoken-glossary/) is your next step! Our glossary will give you a solid understanding of all of the concepts discussed here and others that you might have come across before. This will give you a good insight into the technology keeping your data private, and how to think about your data in your day-to-day digital life.

[FAQ →](/docs/help/faq/)

[Our blog →](/blog/)

[Who is Magaya? →](/docs/help/about-us/)

[Get in touch →](/contact/)

## Thank you <3

Thank you very much for getting this far. We hope you enjoy our service. If you want to keep our service going, we are [funded by the community's donations](/donate/).



