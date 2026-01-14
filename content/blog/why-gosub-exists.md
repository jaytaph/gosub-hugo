---
title: "Why Gosub exists"
date: 2026-01-06
kicker: "Project updates"
subtitle: "A personal story about frustration, ambition, and the joy of building a browser engine from scratch."
author: "Gosub team"
topic: "Engineering & community"
status: "Ongoing"

cta_primary_label: "Join Zulip"
cta_primary_url: "https://chat.developer.gosub.io"
cta_secondary_label: "View GitHub"
cta_secondary_url: "https://github.com/gosub-io/"
---

## The spark: building instead of protesting

A few years ago, I grew deeply frustrated with the state of the current IT and technology landscape. Monopolies are everywhere, with massive companies shaping the internet for their shareholders rather than for users. Since I'm not the type of person to organize protest marches or rally a crowd, my options for doing something about it felt very limited.

But I'm a programmer... I can do programming stuff.

So I decided to write a browser from scratch, in Rust, without having any experience in writing browsers nor experience in Rust. And against all odds, two years later, Gosub is still here.

## What we’re actually building

The goals we set are pretty high. We want to build a browser that is written from scratch and without using an existing engine. We want a browser that is not being controlled by big corporations or greed. We aim for a browser free from legacy complexity, and we want it to be modular and easily reusable for others to implement their own ideas based on top of ours.

This means we are not cloning Chromium and slapping on our own skin. We are literally building the whole browser from the ground up. We need a HTML5 parser, a CSS3 parser, a layout and render engine, an engine to tie everything together, and a JavaScript engine. We are using v8 for now, but external work is underway for a custom JS engine. And there are a ton of other components needed for a fully-functional browser we need to write. It's a huge project where a small army of developers is needed.

## Ambition with a practical milestone

I totally agree that this is very ambitious. Our goal is not to release a browser that can immediately compete with the giants, but we first want a browser that can be used for simple sites and pages. That might seem like a very small step, but it should prove that we can pull it off.

## The team (and reality)

Now for some practical details. How big is our team? Currently, it's just two people. That's not enough. In the early days we had more curious contributors helping out, but life, jobs, interests, and ideas drift. That’s normal. And we have many people lurking around in our Zulip chat, which is always nice.

## How our approach changed

Over the last few years, our understanding of how a browser truly works has grown enormously. We’re no longer just learning: we’re experimenting, prototyping, and exploring new ideas that feel right to us, even if they haven’t been battle-tested yet. We’re not interested in recreating an existing browser line-by-line. Instead, we’re trying to discover better approaches, cleaner designs, and more modular systems that make sense for a browser built today.
