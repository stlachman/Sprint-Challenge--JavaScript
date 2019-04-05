# Sprint Challenge: JavaScript Fundamentals

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a survey of problems. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied variables, functions, object literals, arrays, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a survey of JavaScript problems.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your PM and Instructor in your cohort help channel on Slack. Your work reflects your proficiency in JavaScript fundamentals.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your project manager.

## Description

You will notice there are several JavaScript files being brought into the index.html file.  Each of those files contain JavaScript problems you need to solve.  If you get stuck on something, skip over it and come back to it later.

In meeting the minimum viable product (MVP) specifications listed below, you should have a console full of correct responses to the problems given.

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager

1. Describe the biggest difference between `.forEach` & `.map`.

The biggest difference between the .forEach and .map methods is that .map creates a new array to store the items that are iterated over while with the .forEach method you will need to create a new array and then use the .push method  to move the items into that new array because forEach doesn’t return an array.

2. What is the difference between a function and a method?

A method is a function that is defined as the value of a property or key within an object while a function is defined outside of an object.  Methods are also implicitly given a this keyword when invoked which will reference the object which invoked it, while a function’s this keyword will reference the global object. 

3. What is closure?

A closure in JavaScript occurs when a function is nested within another function. The inner function creates a closure around the outer function, which allows it to access the environment or variables from the outer function even when the outer function has finished executing. Even when the outer function is removed from the execution stack, the inner function retains access to the variable environment of the parent function’s execution environment.

4. Describe the four rules of the 'this' keyword.

Winow or Global Object Binding

If the initial execution of JavaScript occurs within the global execution context, the `this` keyword will reference the global object which is window in the case of a browser.

Implicit Binding

Implicit binding occurs when you invoke a method on an object.  The object upon which the method is invoked will be the context for the this keyword. If a different object is chained to the method, then a different this keyword will be necessary to reference the object from which it came.

Explicit Binding

Explicit binding occurs when you use the methods call, apply, or bind to reference and set the this keyword explicitly on an object.  When creating a constructor function which inherits from a parent constructor function, the call method can be used to invoke the parent constructor function in the context of the child constructor function. It is like running the parent constructor function with the this keyword of the child constructor function. 

New Keyword Binding

When the new keyword is used to create an object from a constructor function, the this keyword references the particular object returned by the constructor function. 


5. Why do we need super() in an extended class?

When the super keyword is used in an extended class, it gives us the ability to call and access the functions and properties associated with the parent constructor.

## Project Set up

Follow these steps to set up and work on your project:

- [ ] Create a forked copy of this project.
- [ ] Add PM as collaborator on Github.
- [ ] Clone your OWN version of Repo (Not Lambda's by mistake!).
- [ ] Create a new Branch on the clone: git checkout -b `<firstName-lastName>`.
- [ ] Create a pull request before you start working on the project requirements.  You will continuously push your updates throughout the project.
- [ ] You are now ready to build this project with your preferred IDE
- [ ] Implement the project on your Branch, committing changes regularly.
- [ ] Push commits: git push origin `<firstName-lastName>`.

Follow these steps for completing your project:

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo).
- [ ] Add your Project Manager as a Reviewer on the Pull-request
- [ ] PM then will count the HW as done by  merging the branch back into master.


## Minimum Viable Product

Your finished project must include all of the following requirements:

**Pro tip for this challenge: If something seems like it isn't working locally, copy and paste your code up to codepen and take another look at the console.**

## Task 1: Objects and Arrays
Test your knowledge of objects and arrays. 
* [ ] Use the [objects-arrays.js](challenges/objects-arrays.js) link to get started.  Read the instructions carefully!

## Task 2: Functions
This challenge takes a look at callbacks and closures as well as scope. 
* [ ] Use the [functions.js](challenges/functions.js) link to get started. Read the instructions carefully!

## Task 3: Prototypes
Create constructors, bind methods, and create cuboids in this prototypes challenge.
* [ ] Use the [prototypes.js](challenges/prototypes.js) link to get started. Read the instructions carefully!

## Task 4: Classes
Once you have completed the prototypes challenge, it's time to convert all your hard work into classes.
* [ ] Use the [classes.js](challenges/classes.js) link to get started. Read the instructions carefully!

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Stretch Problems

There are a few stretch problems found throughout the files, don't work on them until you are finished with MVP requirements!
