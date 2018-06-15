---
layout: post
title: A failed prototype
date: "2018-06-15T21:02:13+10:00"
---

## Ludum Dare

I made a resolution earlier in April this year that I was going to start finishing projects. Around the same time I participated in [Ludum Dare](https://ldjam.com), this is the story of me killing a 48 hour project 60 days later.

Being only a few days into my new resolution of finishing things I was really excited to be participating in Ludum Dare. A 48 hour game jam is the perfect place to start finishing things. The theme came out: "Two incompatible Genres". After only a few minutes of thinking I decide to work around the idea of "a multiplayer singleplayer game". The idea was to make a game which had multiplayer features (chat, other players) but make the game a singleplayer game. The big reveal at the end was going to be that the "other players" were controlled by a big evil AI.

So, I had an idea. I was going to use SDL2 and C++ as my frameworks, I had a tiny bit of starting code (just a sprite class, some collision code, and a basic game loop).

By the time the conclusion of the jam came around I was nowhere near done. I'd bitten off way more than I could chew. I'd spent the first few hours of the jam writing a damn tilemap renderer.

After a day off, I took stock on how I felt about the experience:

1. Next time I definitely need some starting code if I'm using C++ and SDL2.
2. I was really not fond of the idea I'd came up with, it was a stupid joke.

I decided to re-gear the project: focusing on an "electricity" mechanic which I had haphazardly implemented instead of the "mutliplayer singleplayer shtick.

## Post Ludum Dare

So, this concept of electricity: The new idea was "simple".

Your goal is to get to the center of the market to meet the "technology god" and feed him power. You have a battery on your back with a certain amount of power in it. In order to progress you need to complete some challenges, each of these use up bits of power. I originally wanted to have 5 of these challenges, but ended up settling for 3:

1. Hot-starting a switchboard in order to open an electric door
2. Using a flashlight to find your way through a cavern with fake-floorboards in it
3. Using a computer to complete a meta-text adventure

The idea being that when you reached the boss you would 

Here were some problems:

1. Each challenge is a different game to implement. This multiplies the amount of work by A LOT.
2. Even among these challenges the link is strenuous between them, electricity behaves in different ways in each puzzle. There's not much cohesion.
3. I don't like the feeling of paranoia which is created by resource draining games. It's not something I like to experience, maybe other people do (that's cool!).

After a month and a half of working on this project I've decided to can it.

I believe I've completed it to a point where you can extrapolate what the game was going to be, but there just isn't much polish.

The core problem with this whole journey was that I was trying to create a game which manufactured a certain feeling. Manufacturing feelings is HARD. It takes polish. Creating a prototype with polish is difficult when your game can't really be divided into vertical slices easily.

## Lessons Learnt

- Design around a mechanic, not around an emotion
