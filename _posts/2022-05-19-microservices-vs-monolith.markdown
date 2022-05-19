---
layout: post
title:  "Microservices vs. Monolith"
date:   2022-05-19 10:10:00 +0200
categories: Software Architecture
---
An interesting topic I came across today while driving to work, when I listened to a recent post by Dave Farley who discussed the Mono and multi repositories as a reflection to design decisions and how such decisions impact major activities within the team.

The idea that in the recent years the concept of Monolith gained lots of negative reputation and it is considered to be a sin to use such an architectural style. I personally felt ashemed a bit to say "I maintain a monolith... our system is a monolith..." and the typical question I got while interviewing people to join teams I work with: are you planning to move to microservices?

On a recent interaction with someone who joined my team for short period of time, one of the major complains he had about our code base was "this is a monolith application, I can not find anything... it is not clear" and he started splitting things out in order to do microservices.

Dave Farley in his talk lists the goals of having a version control system and why using monolith or true microservices architecture reaps the benefits of using versioning control system, meanwhile how "coupled modules" is the dumb option between these architectural styles. The interesting part for me was the fact that Monolith is not characterized as bad design, it has its place, benefits and usefulness among other styles. I do understand that microservices are the trend now however the complexity overhead is a lot, that is to implement it properly. if done half way, it is basically gathering the worst of all into one. There is nothing wrong in starting in a monolith, especially when there is a business value that needs to be delivered quickly to customers. 

there are lot of ideas that come to mind when talking about this, and lots of these are shared in this [video](https://youtu.be/bWZVx6TgVvc)