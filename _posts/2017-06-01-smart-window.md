---
layout: post
title: "6.115 Final Project: Smart Window"
date: 2017-06-01
---
Have you ever struggled unnecessarily with poorly designed mechanical window shades to adjust the lighting in your room? Have you found yourself unable to achieve the optimal natural light levels in a room due to the limited control offered by window shades and curtains? Are you dissatisfied with the alternative of complementing your space with harsh artificial lighting?

I have long been inconvenienced by suboptimal mixtures of natural and artificial lighting in indoor spaces. I decided to tackle this problem for my [6.115: Microcomputer Project Laboratory](http://web.mit.edu/6.115/www/) final project. My goal was to build a "smart window" that would automatically adjust its level of transparency or opacity to meet a user's preference - like [Transitions lenses](https://www.transitions.com/en-us/) or [Flux](https://justgetflux.com/), but for your window. 

###Background

<!-- TODO: talk about tech behind Transitions lenses, airplane windows, LCD's --> 

<!-- Describe exactly what my vision was --> 

I started by investigating how similar technologies work. **Transitions lenses** are [photochromic lenses](https://en.wikipedia.org/wiki/Photochromic_lens), which contain embedded silver halide or photochromic molecules. These molecules darken when exposed to significant UV light, and are transparent otherwise [0]. While the technology was rather interesting, it was better suited for a chemistry-oriented project rather than an electrical one. 

The [**Boeing 787 Dreamliner**](http://www.boeing.com/commercial/787/) features [self-tinting windows](http://aviationweek.com/blog/787-windows-issue-pics) with a similar visual effect as Transitions lenses, but using a slightly different technology known as [electrochromic glass](https://en.wikipedia.org/wiki/Smart_glass#Electrochromic_devices). Electrochromic glass is a subcategory of "smart glass" in which the amount of light let through the glass is controlled with electricity [2]. They are composed of [electrochromic materials](https://en.wikipedia.org/wiki/Electrochromism) that change color when different amounts of voltage are applied to them [3]. This seemed to fit the bill! Unfortunately, I discovered that it didn't fit the monetary bill - smart glass costs upwards of $100 per square foot, which was well out of my meager project budget of 10 Leeb bucks [4].

###Project Overview

<!-- TODO: high level overview of project, block diagram, etc. -->

###Hardware

<!-- TODO: different mechanical approaches, lasercutting -->

###Software

<!-- TODO: PWM signals, R31JP, PSoC --> 

***

<!-- TODO: conclusion, acknowledgements -->

### References
0. https://en.wikipedia.org/wiki/Photochromic_lens
1. http://www.explainthatstuff.com/electrochromic-windows.html
2. https://en.wikipedia.org/wiki/Smart_glass#Electrochromic_devices
3. https://home.howstuffworks.com/home-improvement/construction/green/smart-window4.htm
4. https://www.technologyreview.com/s/420221/making-smart-windows-that-are-also-cheap/