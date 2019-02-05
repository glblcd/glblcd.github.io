---
layout: post
title:  "GlobalPi: The Raspberry Pi as a teaching computer"
date:   2017-08-18 17:26:04 +0000
---

In July 2017, we ran our first Global Code Summer Programme. One of our challenges was finding the right platform for our students. We wanted everyone in the class to have the same opportunity to learn and grow, so it was important that we bring our own hardware, rather than using whatever was available. We also wanted the flexibility to teach what we wanted  – meaning an IoT-rich curriculum with plenty of coding time using industry-standard tools.

We chose the Raspberry Pi 3B, and this is why.

## Coding
The Raspberry Pi allowed us to dive straight into Linux and Python – the bedrock of our course and the balance of most of the teaching in week #1. Josh and I did all the setup ourselves on the Sunday before kick-off – plugging in, testing, installing Raspbian, then unplugging 30 Pis was the work of a couple of hours.

We don’t do holy wars: Linux is a battle-tested, widely-used OS and every Software Engineer should have a firm grounding in the shell, so we needed to spend a couple of days letting our students discover the terminal, filesystem, editors, and Python REPL. The Raspberry Pi allowed us to do all this without either repurposing whatever hardware the students owned, or supporting a bunch of different configurations in-class.

Finally, Raspbian comes pre-installed with a decent Terminal, some Python editors, and a Python 2.7 (remember, no holy wars) REPL – and a whole bunch of other useful stuff is available with a quick “apt-get”.

## Hardware
The Pi is underpowered for any kind of heavy lifting – I run a tab-heavy Chrome which simply doesn’t fly here – but it’s great for the kind of work we do in class – editing and running Python, looking up documentation, and fooling around with the shell.

Two things that really stand out with the Pi, though –

  * You can see the hardware. The 3B is about the size of a deck of cards – easily small enough to pick up and poke around on. They’re fairly robust so we didn’t use the cases we had in class – on day #1 we spent some time figuring out what all the components did, which really helped to demystify computing hardware.
  * The GPIO pins really help to bridge the gap between programs running in a virtual world where stuff happens but really has no effect, and the physical world where lights flash and bells ring. Being able to extend your computing environment into the real world helped students feel like they really could solve real-world problems with computers.

## Availability
The Raspberry Pi foundation has a truly excellent distribution model, meaning their hardware is available globally, with a short lead time, for a reasonable price.

It was important to us to buy locally, for two reasons:

  * Import and customs logistics is boring, and a place where we really add no value – a prime candidate for outsourcing,
  * We’d much rather build a relationship with a local supplier and let them profit from doing the work.

We were lucky enough to find Isaac Sesi at [Invent Electronics](https://www.inventelectronics.com/){:class="link"}, and took a trip up to Kumasi to pick up the 33 Raspberry Pi starter kits and 6 Arduino starter kits we’d ordered from him. Isaac is a mainstay of the local maker community, and he co-founded the [Nsesa Foundation](http://www.nsesafoundation.org/){:class="link"}, a Ghanaian organisation which aims to inspire students to be innovative using science and technology. He’s top talent and we’re happy to partner with him.

## Portable
The Pi is tiny – it’s lightweight, comes with a screw-on case so you can throw it in your bag, and it’s low-powered so you can run it from a USB socket on the back of a PC (which is what we did). It’s great for teaching a student – but more importantly, for our purposes – it’s great for teaching 18 students! The Pi made our get-in cheap and easy.

## Downsides
Whilst our decision was easy, there are a couple of practical downsides to the Raspberry Pi:

  * **HDMI video** – is all that’s available. Because this is still a fairly new standard it’s difficult to find cheap HDMI monitors on the secondary market. Our labs had multi-input VGA/DVI-D monitors which meant we were able to use a passive HDMI/DVI-D adapter cable, but this is a potential issue in other cases. Similarly, many of our students don’t have HDMI kit at home, which limits their ability to continue learning out of class.
  * **Digital GPIO** – unlike the Arduino Uno, say, the Raspberry Pi can only read digital in – which means the components you use must be set up specially if you need to read more than just 0’s and 1’s. This was fine for us but if you want to read the room temperature or humidity using commonly available components you’ll have to do some more work.
 

The Global Code Summer Programme 2017 finished on July 28. We’ll be back in Ghana in 2018 – find out more on [Twitter](https://twitter.com/glblcd){:class="link"} and [Instagram](https://instagram.com/glblcd){:class="link"}, or get in touch and [buy a Raspberry pi as a gift to a student](https://justgiving.com/GlobalCode){:class="link"}.
