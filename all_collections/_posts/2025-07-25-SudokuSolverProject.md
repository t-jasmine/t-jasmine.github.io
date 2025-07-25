---
layout: post
title: Designing a Sudoku Solver for Hack Club's Athena Award
date: 2025-07-25
categories: [Hack Club]
---

After summer break started, I caught myself staying up late at night...either playing video games or doing sudoku puzzles (surprisingly). I also ended up finding out about Hack Club and one of their YSWS programs called the Athena Award!

Hack Club is a non-profit organization of thousands of teen programmers across the world. For most of their YSWS programs, you code for a certain amount of hours or submit projects and get prizes or invitations to hackathons. Their Athena Award YSWS program is dedicated to those who identify as a girl or non-binary person, and awards whoever completes the program a certification, which is recognized by many reputable organizations, and an invitation to a girl-powered hackathon in NYC! The requirements are to spend 30 hours coding 3 different projects.

For my first project, I had the great idea to tie together my problem-solving hobbies of coding and doing sudoku puzzles! Yet, there are already so many sudoku solvers out there, and some extremely intricate, like this one by Andrew Stuart, which covers lots of complex sudoku-solving techniques, many of which I've never even heard of. I wanted to make something unique and fun, and what better than a sudoku solver where you still have to work for the solution?

To make this project, I used JavaFX and Maven. This was my first time developing a desktop application and using JavaFX and Maven build tools, so I followed along [this video series](https://www.youtube.com/watch?v=wa4ky1ARDkw&list=PLix7MmR3doRqF712ItSp4IhKwJcvDf5M2) by Professor Donald J. Patterson at Westmont College and put my own twist on things! I didn't want to follow a tutorial step-by-step, so I deviated a little and started adding my own features. I thought it'd be fun to make an obstacle for you to tackle before getting the solution. In addition to the mini sudoku mechanic, I also ...

- Added arrow key navigation
- Added a "Solve Cell" button
- Limited textfield character input
- You'll only be able to type digits 1-9 and should only be able to type in 1 character at a time
- If another digit is already in a box, typing another digit will easily replace it
- Modified the appearance of the sudoku grid & other UI
- Fixed other minor logic, organization, and UI issues

This was an exciting first desktop app project! It was definitely a struggle trying to learn how to use different libraries and figuring out how everything works together. At first, I tried to create a .msi type executable file, where you launch an installer to get the app, but I ran into a lot of errors getting it to work on other computers, so I ditched that idea... but I think I'll explore it in another project! This project took me more hours than I expected, considering its simplicity, but it was well worth it testing out different features of JavaFX throughout development.

Want to see test out and see my code? The repository is linked [here!](https://github.com/t-jasmine/Sudoku-Solver)