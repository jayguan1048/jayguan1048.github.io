---
layout: essay
type: essay
title: "Coding Standards: To Understand a Language"
# All dates must be YYYY-MM-DD format!
date: 2026-02-12
published: true.
labels:
  - Coding Standards
---

<img width="200px" class="rounded float-start pe-4" src="../img/eslint.png">

Coding standards certainly are something that can seem rather trivial. Much of it can get reduced to simply style and how you format your code, but that style is rather important as readability is always relevant in code. These coding standards help instill good habits, so that code doesn't get too clustered and hard to parse for when multiple people inevitably have to look at and work with code we write. Outside of that general case, however, these coding standards do help to promote understanding of a language because it can help introduce structure and force you to gain at least somewhat of an understanding of what you are doing, rahter than slapdashing together a solution and hoping it works. These coding standards introduce a set of rules that must be followed, often requiring more and more specifics get introduced, so more in-depth knowledge becomes required to be able to adhere to these rules. Vague sentiments and solutions become more refined out of necessity. Having to work with ESLint this past week has helped me refine my typescript skils a bit, despite how tedious some of it became, adn being able to read all those errors helped me learn what I was doing wrong and how to fix them.

## Using ESLint

ESLint was actually very helpful for me, despite how tedious some of the errors it gave were at times. Most of the time it was catching minor issues as I was working my way through the code, require new lines at the end of files, forbidding unnecessary spaces, and so on and so forth. There was also minor things like using single quote strings rather than double quotes. However, once I had gotten my solution down, the errors it gave did show a few improvements that coudl be made, that made me have to learn more about typescript. For instance, I learned about the unknown varibale type when I was forced to wrtie a function that accepted various object types into a singular array, making the actual paramaters and return types an unclear data type to be assigned. It also gave clear erros for me to look through, so that I could troubleshoot easier, by looking at what specific issues I was getting, whether it be data type mismatch, or simple spelling errors. Of course, at times it did become an annoyance, especially when I was under a time crunch which is a common occurence under the structure of these assignments. 

## Conclusion

Coding standards are simply another tool that can be used to put your feet to the fire, so to speak. Forcing yourself to work under specific rules, forces you to actively interact with the language you are using and have actually presentable code. With ESLint, it was especially helpful because it would list the issues as errors, that it would return to you. In general though, unless you implement something to keeep track of that for you, coding standards are something that you are just going to have to keep track of yourself, which in a sense, could promote responsibility. Another way of looking at it, is as a form of preparation for job or client specifications, where you won't always be able to just do whatever you want, as your job requires some specific elements or formatting. Adding restrictions is a rather effective way to help you learn and be creative.
