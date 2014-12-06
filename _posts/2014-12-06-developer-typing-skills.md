---
layout: post
title: "Is fast typing required for a developer? I changed my mind on this"
tags:
---

There is a sentiment that developers need to be able to type really fast because we "type code for a living".

I've long rejected that idea, and not just bacause lines of code is the worst possible metric for productivity. My main reason was that a good dev workflow normally entails much, much more reading than writing. Also, communication skills for design discussions, whiteboarding, etc. seems more important to me. And don't just good old thinking. I thought fast typing was merely a nice to have, and I never really invested time into improving mine.

But reading the great book "Thinking, Fast and Slow" by Daniel Kahneman showed me a flaw in my view (there's so much substance in there, I'm sure I'll get many more insights from it).

The insight is this: 
-Explixit, conscious thinking (which I believe paramount to development) takes a lot of mental energy. 
-Like physical stamina, we literally have a limited pool of mental energy.
-Any other task that needs our conscious attention depletes our mental stamina, leaving us with less good thinking. 
-Unconscious, automatic processing takes less of a strain (like strolling or breathing).
-Therefore, in order to do better and more good conscious thinking (as is required in solving programming problems), we need to minimise non-automatic activities.

From this we can see that an activity like correcting a typing mistake or looking at the keyboard will tap our "thinking stamina", but when it becomes fully unconscious/automatic it will free up some space for productive problem solving. Hence, it's important that we learn to type automatically, rather than fast, although fast is a side effect of automatic.

This line of thinking can be taken much further than just typing. Anything in our dev environment that is not automatic, like looking for a menu with some function, or doing an explicit compile, will waste our mental stamina. It is therefore really important to:
(1) Know your dev tools, including common shortcuts and navigation tools. Keeping it simple is a easy way to achieve this. This has similar benefit to automatic typing.
(2) Cut out explicit tasks. First thing that comes to mind is compiling. The Ruby and other dynamic lang guys have been doing this for years, continuously running tests in the background that shows you the impact of changes, instead of a compile, run action. Some great tools in static world, like Resharper and NCrunch helps here. Another is deploying - the whole continous delivery movement applies here. Tools like JRebel in Java world can also help.

In summary: find ways to automate repeditive things that draws your attention and you will have a lot more time for good thinking and happy developement. I, for one, will take these things more seriously now.


