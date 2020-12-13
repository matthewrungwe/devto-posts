# Writing code that is clean and code that inspires.

So, finally you now know how to write code or you have been doing it for a while but do you still feel like you could be doing more? A good place to start will be to go through your projects and take a closer look at the code that you have written and see if you can make it better.

In this article we are going to look at a few ways that can help you to start writing not only code that is clean but code that inspires others. My hope is that after this read, you will be able to have a different approach in the way to structure your files and also have a few ideas of where to begin with process.

## Table of Contents

1. [Change your mindset](#change-mindset)
1. [Use comments](#comments)
1. [Separate concerns](#separating-concerns)
1. [Follow best practices](#best-practices)
1. [Refactor whenever you can](#refactor)
1. [Use descriptive variable names](#descriptive-variables)
1. [Be consistent](#consistency)
1. [Learn from others](#learning-from-others)
1. [Learn to read the documentation](#read-documentation)
1. [Review your own code](#code-review)


---

<h3 id="change-mindset">Change your mindset</h3>

At some point in your journey you will placed in a position to share your work. For some it may be sooner and others even a little later in their career. Carry the mindset that you are not just writing for yourself, you are writing for others. So, keep in mind that one day someone will go through your work and I believe you would love to see a smile on their face and a nod of respect.

<h3 id="comments">Use comments</h3>

Simple right? Then why do we forget to do it. The beauty of writing comments sometimes it's not just for the next person, sometimes it's actually for yourself. 

Sometimes I find myself taking hours just to understand the code I wrote a few weeks or months back. You can quickly become a stranger to your own code. Now think, if you sometimes struggle with this, how about handing over a file like that to a colleague, a friend or a mentee. They would be disappointed if not hurt by the time they will need to spend just to understand the meaning of code you wrote.

<h3 id="separate-concerns">Separate concerns</h3>

If you have been coding for at least a few weeks, I am sure you have asked yourself if there maybe another way to organise your code. It is important to separate functionality in the applicatioin that you are developing. As your application gets bigger and more complex, you need to be able to maintain it and there is no better way than to isolate each feature of the application into separate files. Guys in Computer Science will call this a loosly coupled system.

This idea can be as simple as writing HTML in it's own HTML file and writing JavaScript in it's own JavaScript file just so there will be a little order in your code. It can get as complicated writing your own API or base code that will depend heavily on modules that will communicate using import statements. 

<h3 id="best-practices">Follow Best Practices</h3>

Best practices are standard approaches that have been proven to produce effective results. These techniques (ways of doing things) are not there to guard you from being unique or creative but rather guide you towards developing systems that dont'd fall too far off from the standard scale. 

The other beauty of best practices is that there will always be a lot of resources out there to assist you in solving the problems you come accross during development or maintenance.  

<h3 id="refactor">Refactor whenever you can</h3>

In addition to best practices, refactor as you go because you might not have enough time to come back and redo your code especially when you are working on a tight deadline. 

In JavaScript, there were so many features that came with ES6: arrow functions, template literals, tenary statements, symbols, destructuring just to mention a few. In HTML we can now use semantic HTML elements which can even substitute a lot of ARIA attribute to improve accessibility.

Not only do these features simplify your code, you can also see a reduction in your file sizes which may not seem important in development but may very well play a role in the performance of your application in production.

<h3 id="descriptive-variables">Use descriptive variable names</h3>

Really Matthew? YES. I was part of the MWS Mentor Team for the Google Africa Developer Scholarship 2020 and had the priviledge to review some of the projects submitted by students during the second phase. Some of the students would use variables like "ho" for "hour" and "hu" for "humidity" because thehy were building a Weather Web App. While to them it made sense but to others, it was painful. 

Use variables that are meaningful and that describe the purpose they have been created for. Try not to use single letter variable names like "x" or "y" unless you are actually dealin with axes.

<h3 id="consistency">Be consistent</h3>

As much as wewant our code to look the same, it's a little hard. We all have a signature in our code, our way of doing things we say. Well, pick up a style and stick to it. If you prefer to have loosly defined variales or have them tied to an object, it's okay. However, try to maintain that approach through out your projects. 

Consistency may range from the code that you actually write to the architecture and technologies. If you are using a [SASS](https://sass-lang.com) as your CSS preprocessor try to hold to it throughout and not add [LESS](https://lesscss.org) in the process.

<h3 id="learning-from-others">Learn from others</h3>

As much as we don't want to admit it, there are some people that know how to do things better maybe because they have more experience but sometimes it's because they have spent a lot of time perfecting their technique and researching.

I improved my files structure by observing others mostly [Angular](https://angular.io) forlders if you create them using the CLI and [HTML5 Up](https://html5up.net) projects. I learnt how to organise my Data, Services and Interfaces from Deborah Kurata's code files on Pluralsight. 

Sometimes they way others do it just works. Don't wait to figure it out own when someone can save your years of work by learning from them.

<h3 id="read-documentation">Learn to read the documentation</h3>

This one is an interesting one. I was quite surprised when this idea popped up in my mind when I was planning this article. I am guilty of not spending enough time in the documentation but it's something I am working on and I thought it would be nice to share anyway. 

Reading the documentation allwos yo to stay up-to-date with the advancements in the technologies that you are using. You can adobt these inprovements into your projects to save yourself from any vulnerabilities and to stay at the to of your game with updated projects or content. 

I was inspired by [Lea Verou](https://lea.verou.me), [Deborah Kurata](https://blogs.msmvps.com/deborahk), [John Papa](https://johnpapa.net) and [Brad Traversy](https://www.traversymedia.com) from my courses on [Pluralsight](https://www.pluralsight.com). They also happen to be experts in the Web Development industry.

<h3 id="code-review">Review your own code</h3>

It always amazes me how much changes I make when when I just dedicate a few hours to go through what I have written. Take a closer look at the code you have written and speak in third person or in an interogating way, "it there another way you could have written this" or "are you sure there aren't any mistakes or misreferences". 

It's always a good thing to go through your code again. You will always find some changes to make: it might be a comment to add or a better way to implement a function. This idea does not have to be independent to code alone, it can also apply to other aspects of life. Just take some time to go through what you do again and you will ba amazed at the improvements you can make.  

---

*Writing code that inspires can take some time to be good at but it is not impossible*. Try each time to improve the way you write your code and eventually you will get there because you can only get better if you try.

In summary, write you code as though you are writing it for a team and that it might potentially be a big thing tomorrow



