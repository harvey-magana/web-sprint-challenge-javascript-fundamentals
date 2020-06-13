# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a survey of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your TL if you need direction. 

_You have **three hours** to complete this challenge. Plan your time accordingly._


## Introduction

You will notice there are several JavaScript files being brought into the index.html file.  Each of those files contain JavaScript problems you need to solve.  If you get stuck on something, skip over it and come back to it later.

In meeting the minimum viable product (MVP) specifications listed below, you should have a console full of correct responses to the problems given.

### Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your team lead as the evaluate your solution.

## Interview Questions

Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. You might prepare by writing down your own answers before hand.

1. Briefly compare and contrast `.forEach` & `.map` (2-3 sentences max)
    With `.forEach`, you need to provide an external array to be iterated over. This array method also cannot provide an altered array unless you assign a variable that is an array so that it can put the results there. 

    With the `.mapj` method, everything is done in one place. It can take an array and make a new array from the callback function inside. 

    The characteristics they share are that they are both array methods, they are interator functions, they house a callback function to get their work done. 

2. Explain the difference between a callback and a higher order function.
    Higher order functions are functions that accept another function as an argument. 
    Callback functions are that function passed in as the argument. 

    Array methods are a good example of higher order functions because part of what they are is that they can accept a callback function as a parameter inside of them. 

    Callback functions can be declared functions or they can be anonymous functions that get passed into the parameter as an argument into the higher order function and are returned. 

3. What is closure?
    Closure emerge at the time that a function is created. Within the scope of a funciton a lexical environment is created. This internal environmet shields variables and functions from the global scope or the scope that is outside of the more inner scopes. This state of being inside of the scope gives this data some privacy as well. The inner most function will have access to all of the outer environments up to the global scope. None of the outer scopes will have access to the inner scopes. 

4. Describe the four rules of the 'this' keyword.
    Rule 1: Window/Global Object Binding, when 'this' is called in the console of a browser, the Window object will be returned. 
    Rule 2: Implicit Binding, Whenever a preceding dot calls a function, the object before the dot is this. 'this.doSomething...'
    Rule 3: New binding, Whenever the 'new' keyword is used to create an object, 'this' inside of the funtion is referring back to itself depending on the methods and properties that the constructor is making. 
    Rule 4: Explicit binding, When using methods like .call() or .apply(), 'this' is pointing to the parameter that the method is used in. 

5. Why do we need super() in an extended class?
    The use of super() is necessary in classes when a parent class must pass its properties down to its children classes. 

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Project Set Up

> This section should include instruction for the sprint challenge. These should only cover things that are _not_ being evaluated by the challenge itself, e.g. environment/project setup, link to a starter project, etc. In general, this will be the following Git fork, clone, branch, commit, push, create pull request flow, though may need to be adapted for some specific challenges.

- [ ] Create a forked copy of this project
- [ ] Add your team lead as collaborator on Github
- [ ] Clone your OWN version of the repository (Not Lambda's by mistake!)
- [ ] Create a new branch: git checkout -b `<firstName-lastName>`.
- [ ] Implement the project on your newly created `<firstName-lastName>` branch, committing changes regularly
- [ ] Push commits: git push origin `<firstName-lastName>`

### Task 2: Project Requirements

Your finished project must include all of the following requirements:

**Pro tip for this challenge: If something seems like it isn't working locally, copy and paste your code up to codepen and take another look at the console.**

#### Task A: Objects and Arrays

Test your knowledge of advanced array methods and callbacks.
* [ ] Use the [arrays-callbacks.js](challenges/arrays-callbacks.js) link to get started.  Read the instructions carefully!

#### Task B: Closure

This challenge takes a look at closures as well as scope. 
* [ ] Use the [closure.js](challenges/closure.js) link to get started. Read the instructions carefully!

#### Task C: Prototypes

Create constructors, bind methods, and create cuboids in this prototypes challenge.
* [ ] Use the [prototypes.js](challenges/prototypes.js) link to get started. Read the instructions carefully!

#### Task D: Classes

Once you have completed the prototypes challenge, it's time to convert all your hard work into classes.
* [ ] Use the [classes.js](challenges/classes.js) link to get started. Read the instructions carefully!

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

### Task 3: Stretch Goals 

There are a few stretch problems found throughout the files, don't work on them until you are finished with MVP requirements!

## Submission format

Follow these steps for completing your project.

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo). **Please don't merge your own pull request**
- [ ] Add your team lead as a reviewer on the pull-request
- [ ] Your team lead will count the project as complete after receiving your pull-request


