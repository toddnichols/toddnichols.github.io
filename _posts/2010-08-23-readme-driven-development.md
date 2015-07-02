---
layout: post
title: Readme Driven Development
---

{{ page.title }}
================

<p class="meta">23 August 2010 - San Francisco</p>

I hear a lot of talk these days about TDD and BDD and Extreme Programming and SCRUM and stand up meetings and all kinds of methodologies and techniques for developing better software, but it's all irrelevant unless the software we're building meets the needs of those that are using it. Let me put that another way. A perfect implementation of the wrong specification is worthless. By the same principle a beautifully crafted library with no documentation is also damn near worthless. If your software solves the wrong problem or nobody can figure out how to use it, there's something very bad going on.

Fine. So how do we solve this problem? It's easier than you think, and it's important enough to warrant its very own paragraph.

Write your Readme first.

First. As in, before you write any code or tests or behaviors or stories or ANYTHING. I know, I know, we're programmers, dammit, not tech writers! But that's where you're wrong. Writing a Readme is absolutely essential to writing good software. Until you've written about your software, you have no idea what you'll be coding. Between The Great Backlash Against Waterfall Design and The Supreme Acceptance of Agile Development, something was lost. Don't get me wrong, waterfall design takes things way too far. Huge systems specified in minute detail end up being the WRONG systems specified in minute detail. We were right to strike it down. But what took its place is too far in the other direction. Now we have projects with short, badly written, or entirely missing documentation. Some projects don't even have a Readme!

This is not acceptable. There must be some middle ground between reams of technical specifications and no specifications at all. And in fact there is. That middle ground is the humble Readme.

It's important to distinguish Readme Driven Development from Documentation Driven Development. RDD could be considered a subset or limited version of DDD. By restricting your design documentation to a single file that is intended to be read as an introduction to your software, RDD keeps you safe from DDD-turned-waterfall syndrome by punishing you for lengthy or overprecise specification. At the same time, it rewards you for keeping libraries small and modularized. These simple reinforcements go a long way towards driving your project in the right direction without a lot of process to ensure you do the right thing.

By writing your Readme first you give yourself some pretty significant advantages:


Consider the process of writing the Readme for your project as the true act of creation. This is where all your brilliant ideas should be expressed. This document should stand on its own as a testament to your creativity and expressiveness. The Readme should be the single most important document in your codebase; writing it first is the proper thing to do.
