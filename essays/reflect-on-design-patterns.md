---
layout: essay
type: essay
title: "A Reflection on Design Patterns"
# All dates must be YYYY-MM-DD format!
date: 2025-07-24
published: true
labels:
  - Software Engineering
  - Learning
  - Computer Science
---

## Learning to Cook Without Burning the Kitchen Down
At some point during my summer, coding started to feel a little like cooking. You start with a recipe - maybe a tutorial from class, maybe something you found online. You follow the steps, it works (kind of), and you feel good about it. But as soon as you try to tweak something or build your own "dish" from scratch, things fall apart. Functions start doing too much, code gets tangled, bugs creep in. It felt like every time I tried to make a small change, something else broke. I was building spaghetti, and not in a good way.

That’s when I first heard about design patterns, something developers actually use in the wild to stop writing messy code. I learned that design patterns are more like cooking techniques. You can improvise all you want, but knowing the difference between sautéing and searing saves you from burning dinner. Same thing with code: knowing the difference between a Singleton and a Factory can save you from burning your project.

## Not Magic, Just Muscle Memory
What I’ve learned is that design patterns aren’t magic. They don’t make your code good by default. But they do give you proven solutions to common problems. It’s like learning how to use a whisk, or how to dice onions properly. You don’t have to think about it every time—you just use it because you know it works.

Sure, I still get confused sometimes. I mix up the Decorator and Adapter patterns. I don’t always know when a Strategy Pattern is better than just using polymorphism. But each time I run into a problem and realize there's a pattern for it, I feel like I’m slowly leveling up as a developer.

## A Pattern That Saved the Day
There’s one pattern I’ve really grown to appreciate: the Singleton Pattern. I know it gets a bad reputation sometimes, but for our database handler in a recent web app project, it made a huge difference. We needed a single, shared connection to our SQLite database across multiple parts of the app, and we didn’t want to accidentally open multiple connections. One static instance later, problem solved. No more duplicated connections, no more random crashes.

Was it perfect? No. Was it better than the alternative? Definitely.

## Final Thoughts
I used to think that good code just came from writing lots of it. And sure, practice helps, but design patterns have taught me that structure matters just as much as syntax. Patterns help you build things that last, and that you or your teammates can actually understand later.

Now, when someone asks me in an interview, “What are design patterns?” I don’t just say “reusable solutions to common problems.” I think about how they helped me turn a jumbled mess into something I’m proud to show off. And when they ask, “Which patterns have you used?”, I can smile and talk about Observers, Commands, and the good ol’ Singleton that saved our app from crashing.

I am still learning, but I know one thing for sure: I’ll never write another serious project without leaning on design patterns. They don’t just help you write code, they help you write better code.

