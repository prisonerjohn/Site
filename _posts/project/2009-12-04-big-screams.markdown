---
layout:	project
categories:
- project
title: "Big Screams"
img: big-screams-main.jpg
thumb: big-screams-thumb.jpg
iframe: '<iframe src="https://player.vimeo.com/video/8487873?title=0&byline=0&portrait=0" width="945" height="532" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>'
carousel:
- big-screams-01.jpg
- big-screams-02.jpg
- big-screams-03.jpg
- big-screams-04.jpg
- big-screams-05.jpg
tags: 
- experimental
- installation
- mobile
- ITP
- openFrameworks
- Processing
---
Big Screams is a participative mobile phone game played on a giant screen.

Players dial the on-screen phone number to create their critter. Each phone number generates a unique critter so yours will look identical every time you call. Critters can have various shapes, colours, and sizes, so each user will have a unique representation on screen. Each critter is also tagged with the caller’s phone number so that it is easily recognizable by its owner.

Once the call connection is established, participants scream into their phones to control their critter, which opens and closes its mouth in sync with the amplitude of the scream. At any given moment, the critter associated with the loudest screamer is attracted to the centre of the screen and repels all others away from it. If a critter falls out of the screen’s bounds, it gets disconnected and the caller must dial again to get back into the game. The object is therefore not only to scream the loudest, but to scream the loudest for the longest period of time.

You’re not supposed to scream in public places, but that’s exactly what you have to do to play the game. Big Screams allows people to revisit the boundaries of socialized behavior, to reconnect with this primal mode of expression and experience the resulting powerful catharsis.

The Big Screams front-end is built in C++ using the [openFrameworks](http://www.openframeworks.cc/) and [Box2D](http://box2d.org/) libraries. The back-end is built with [Processing](https://processing.org/) and synchronization is done using the [Most Pixels Ever](https://github.com/shiffman/Most-Pixels-Ever-Processing) library. The call system is provided by [MegaPhone](http://www.megaphonetv.com/).

#### Publications

_“Today’s designers are creating compelling atmospheres and interactive experiences by merging hardware and software with architecture and design. This book is a collection of this innovative work produced where virtual realms meet the real world and where dataflow confronts the human senses. It presents an international spectrum of interdisciplinary projects at the intersection of laboratory, trade show, and urban space that play with the new frontiers of perception, interaction, and staging created by current technology. The work reveals how technology is fundamentally changing and expanding strategies for the targeted use of architecture, art, communication, and design for the future.”_ – [A Touch of Code](http://shop.gestalten.com/a-touch-of-code.html), [Gestalten](http://shop.gestalten.com/), Apr 2011.

{% include carousel.html %}
