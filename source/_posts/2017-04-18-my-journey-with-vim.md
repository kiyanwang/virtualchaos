---
title: My Journey With Vim
date: 2017-04-18 11:22:20
tags: vim, development
---

I've been using Vi/Vim to edit files on servers for almost two decades. I had to learn to use it because it was always available on remote servers, so like it or not it was important to be able to use it. I became fairly competent with it, but for most of that time it never occurred to me to consider using it for actual development. Especially not in a world where I had tools [Sublime Text](https://www.sublimetext.com/) and [IntelliJ Idea](https://www.jetbrains.com/).

My real journey with Vim as my primary editor really began about five years ago. I'm not sure why I thought it was a good idea at the time, what I do know is that my first attempt to switch over to it was an abysmal failure, one that perfectly echoes this quote from Nietzsche:

> *He who would learn to fly one day must first learn to stand and walk and run and climb and dance; one cannot fly into flying* ~ Friedrich Nietzsche

My problem was that I tried to *fly into flying*. I *thought* I understood the basics of Vim and therefore I could dive right into using a preconfigured Vim distribution, [SPF13](http://vim.spf13.com/). Let me add that there's nothing wrong with SPF13, it's just wasn't the right place to start for me.

I set off on the wrong foot, and after struggling with it for a few weeks, I gave up. It wasn't Vim that I was battling with but rather the customisations in the distribution I was using, which I don't doubt work really well for many people but it ruined my mental model and led to immense frustration.

Now fast forward a couple of years. Although I was still tinkering with Vim I had been using IntelliJ solidly for all my development work, and for the most part enjoying it.

At [work](https://www.talis.com) we refactored some of our monolithic codebases into micro services. We chose not to go down the monorepo route which meant developers had multiple git repos checked out each with its own development environment provisioned through Vagrant. I found myself having to switch between multiple projects and more often than not having to edit code in several repos as we refactored and moved more of our code around.

This is where I started to struggle with IntelliJ. It works great if you have a single window open with a large code base, but it works less well when you need 4 or 5 projects open at once. I routinely found my 16GB MBP grinding to a halt under the burden of multiple instances of IntelliJ running along with multiple VM's (this was before we began [dockerising](https://www.docker.com) everything).

I couldn't get away from having to run multiple VM's locally and had to accept that they would consume memory and cpu. But, could I do something about the GB's of memory my IDE was constantly consuming, not to mention CPU as it reindexed code.

This is when I started looking at Vim again. As I mentioned a few moments ago, I had continued tinkering with it (sans SPF13), and had developed a new found respect for it. I consciously made a mental note that this time I would take it slowly and see how far I could get, I had learned my lesson

> *A beginning is the time for taking the most delicate care ...* ~ from the manual of Muad'Dib by the Princess Irulan

The first month or so was difficult, but soon after that I found things becoming easier. I began customising my Vim setup adding plugins and configuring it around my needs and my own quirks. I took care to only add something to my '.vimrc' file if I understood what it did, and with plugins I made sure that I only kept the ones I was actually using, and routinely cleaned out ones that I had tried but didn't think I was getting any value out of.

