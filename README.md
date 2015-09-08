# Tutorial Example: React.js

How to run this tutorial: Clone this repo! Hooray; that was step one. Then run `npm install` to get your own copy of the node_modeles. Next, run `node app.js` so that your server with comment data is up. Finally, open `index.html` in your browser. Then comment away!


## Why did you choose this subject? How were you first made aware of it?

We chose to learn React.js in order to build on the concepts introduced in the mini-lesson from several weeks ago.

## What problem does it solve? How does it solve the problem (conceptually)? Why does one use it?

React.js is great for large applications with data that change over time. It aims to simplify the problem of changing data by working only with the VIEW layer (the V in MVC) and building custom HTML "components" to render the data in the DOM.

## What are the alternatives? What is it similar to, if anything?

The alternative would be a templating engine such as Handlebars, which would work just as well—if not better—for a small application. It's hard to compare React to other frameworks, because it's not a full framework, but it kind of combines the VIEW layers of Backbone and Angular, in a way.

## What is the history of this technology? Who built it and why? Who is maintaining it?

React is really new, so it doesn't have much history. Facebook built it and is maintaining it.

Here's the perspective of one of the FB engineers who developed React, addressing the concern that React is putting logic back into HTML:

`"We all remember the days of mixing our PHP in with HTML. Code was really hard to maintain and security was an afterthought. We do not want to go back to those days.`

`Since those days, we have developed client and server-side templating languages to prevent engineers from committing this sin. However, these templating languages have a cost: they make building user interfaces harder. Doing something simple like alternating row colors in a table requires jumping through hoops in many languages.`

`What we should do instead is accept that user interfaces are becoming more and more complicated and that we need a real programming language (with all of its expressive power) to build user interfaces at scale.`

`React is a library that embraces this idea. React still encourages separation of concerns: components fulfill only the role of the "view" in a traditional MVC application. However, instead of an oversimplified templating language, you get to use JavaScript to build abstractions and reuse code."`

## What is your opinion on the technology after having built something with it? What are the biggest conceptual hurdles (if any) you encountered when researching this?

The React.js documentation isn't great, which makes it hard for a beginner to conceptualize. There are new concepts—like "props" and "components"—that, with a smaller application, seem unwieldy and unnecessary. But it seems like a powerful tool if you learn it well enough! Once we had the initial script written, we were able to take this script and add it to an existing rails app, running the comments from a node server and rendering them in the rails layout.html.erb file.


## What resources do you recommend for interested students? What article or forum was most helpful to you in learning this?

We worked through the React.js tutorial for building a comment box: https://facebook.github.io/react/docs/tutorial.html

We also liked this blog post, "React for Stupid People": http://blog.andrewray.me/reactjs-for-stupid-people/

## What are 3 interview questions one might be asked about this technology?

1. Compare and contrast Angular, React, and Backbone as MVC frameworks. (tip: TRICK QUESTION! React isn't a complete framework...)

2. When would you recommend using React over a basic templating engine?

3. Explain the concept of a virtual DOM and how React uses the virtual DOM to update the DOM rendered in the browser.
