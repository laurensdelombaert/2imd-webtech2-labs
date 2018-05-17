# 1. Portfolio Laurens De Lombaert

In dit bestand kan u mijn werken voor het vak Webtech 3 [YP5536] raadplegen. Voor vragen kan u mij DM'en op [@LauDeLombaert](https://twitter.com/LauDeLombaert)

## 1.1. Table of Contents

<!-- TOC -->

- [1. Portfolio Laurens De Lombaert](#1-portfolio-laurens-de-lombaert)
    - [1.1. Table of Contents](#11-table-of-contents)
    - [1.2. Classes](#12-classes)
        - [1.2.1. Exercise 1: Git-it](#121-exercise-1-git-it)
            - [1.2.1.1. Git-it screenshot](#1211-git-it-screenshot)
        - [1.2.2. Exercise 2: Flexbox & CSS Grids](#122-exercise-2-flexbox--css-grids)
            - [1.2.2.1. Flexbox Froggy](#1221-flexbox-froggy)
            - [1.2.2.2. CSS Grid Garden](#1222-css-grid-garden)
        - [1.2.3. Exercise 3: ECS6](#123-exercise-3-ecs6)
            - [1.2.3.1. Articles](#1231-articles)
            - [1.2.3.2. Links](#1232-links)
        - [1.2.4. Exercise 4: NodeJS](#124-exercise-4-nodejs)
        - [1.2.5. Exercise 5: Web Sockets](#125-exercise-5-web-sockets)
            - [1.2.5.1. Extra miles](#1251-extra-miles)
        - [1.2.6. Sass and BEM](#126-sass-and-bem)
        - [1.2.7. Build tools](#127-build-tools)
            - [1.2.7.1. Intro](#1271-intro)
            - [1.2.7.2. CSS](#1272-css)
            - [1.2.7.3. JS](#1273-js)
            - [1.2.7.4. BrowserSync](#1274-browsersync)
            - [1.2.7.5. Beyond](#1275-beyond)
        - [1.2.8. Project Building](#128-project-building)
        - [1.2.9. Kweeni Team](#129-kweeni-team)
            - [1.2.9.1. "Routes"](#1291-routes)
    - [1.3. MongoDB University](#13-mongodb-university)
        - [1.3.1. M001](#131-m001)
            - [1.3.1.1. Chapter 1: Introduction](#1311-chapter-1-introduction)
            - [1.3.1.2. Chapter 2: The MongoDB Query Language + Atlas](#1312-chapter-2-the-mongodb-query-language--atlas)
        - [1.3.2. M101JS](#132-m101js)
            - [1.3.2.1. Week 1: Introduction](#1321-week-1-introduction)
            - [1.3.2.2. Week 2: CRUD](#1322-week-2-crud)
            - [1.3.2.3. Week 3: The Node.js Driver](#1323-week-3-the-nodejs-driver)
            - [1.3.2.4. Week 4: Schema Design](#1324-week-4-schema-design)
            - [1.3.2.5. Week 5: Indexes and Performance](#1325-week-5-indexes-and-performance)
            - [1.3.2.6. Week 6: The Aggregation Framework](#1326-week-6-the-aggregation-framework)

<!-- /TOC -->

## 1.2. Classes

### 1.2.1. Exercise 1: Git-it

Team 6 repo: <https://github.com/laurensdelombaert/laboTeam6>

#### 1.2.1.1. Git-it screenshot

![Printscreen GIT-IT](http://laurenk170.170.axc.nl/webtech/gitit.png)

### 1.2.2. Exercise 2: Flexbox & CSS Grids

Codepen: <https://codepen.io/laurensdelombaert/pen/vdzBEr>
Upload test domain: <http://laurenk170.170.axc.nl/webtech/grids/watis.html>

Team 11 repo: <https://github.com/laurensdelombaert/laboteam11>

#### 1.2.2.1. Flexbox Froggy

![Printscreen GIT-IT](http://laurenk170.170.axc.nl/webtech/froggy.png)

#### 1.2.2.2. CSS Grid Garden

![Printscreen Grid-garden](http://laurenk170.170.axc.nl/webtech/grid.png)

### 1.2.3. Exercise 3: ECS6

#### 1.2.3.1. Articles

Article about ECS6 for loops: <https://hacks.mozilla.org/2015/04/es6-in-depth-iterators-and-the-for-of-loop/>
New in ECS6 website: <http://es6-features.org/>

#### 1.2.3.2. Links

Codepen: <https://codepen.io/laurensdelombaert/pen/LQqJQM>

Github Repo: <https://github.com/laurensdelombaert/webtech-portfolio>

### 1.2.4. Exercise 4: NodeJS

Github Repo (watis branch): <https://github.com/laurensdelombaert/laboteam11/tree/watis>

Heroku app: <https://laurensdelombaert-kweeni.herokuapp.com/kweenie/wat-is-express-js-en-waarvoor-dient-het>

### 1.2.5. Exercise 5: Web Sockets

Github Repo: <https://github.com/laurensdelombaert/webtech-sockets>

Heroku app: <https://growl-sockets.herokuapp.com/>

#### 1.2.5.1. Extra miles

- Fade in animation on loading pages
- Responsive CSS
- SVG Circles for showing %
  - Circles are animated with transitions
- Visual feedback for voting
  - If you can vote, options will transition to a green bg.
    - There will be an animation for UX if you vote as well.
  - If you can't vote, after the first attempt this transition will be red.
    - There will be a shake animation as well to show you can't vote.
- After inserting the last answer, a new answer field will appear.
  - Thus you can create infinite answers for a poll
- You can vote only once with localhost
  - not waterproof without login system
- The form will not write the data over primus if you didn't fill in the question and at least two answers
  - Not correctly filling in will add feedback to the invalid fields.
- Placing the question will show a feedback dialog, including animations.
- ... (see code)

### 1.2.6. Sass and BEM

After the Sass and BEM classes I've been working on converting my existing projects with these standards. To prove my skills and understanding I shall be writing the css of my app for Product Lab with Sass and BEM.

### 1.2.7. Build tools

During this week I've learned a lot about efficient build tools through Gulp. Instead of having to do a lot of tasks manually each time while coding, most processes can be automated.

#### 1.2.7.1. Intro

As a starter, I've learned how to auto compile SASS (Pre-CSS) to CSS and to compress it live while working on the styling. From this point I've begun researching other possibilities of Gulp by extending my CSS watcher task. I've discovered about adding sourcemaps to the pipelines for inspecting with the original source code in my browser.

#### 1.2.7.2. CSS

By working more with the CSS buil dtools, I was daydreaming about previous classes from webtech on my way home. I remembered the talk about Post-CSS in the road map for front-end web developers and I got the idea to mix Pre-CSS and Post-CSS into one build tool.

When I got home I immediately started experimenting with this and doing some [research](https://gist.github.com/renarsvilnis/ab8581049a3efe4d03d8). Eventually, I discovered [CSSNano](http://cssnano.co/), which was in [benchmarks](http://goalsmashers.github.io/css-minification-benchmark/) among the best minifyers for CSS. I also got to learn about [CSSNext](http://cssnext.io/), allowing to write future-proof CSS, with backwards compatibility to even Internet Explorer 10. There seem to be countless of other post-processors as well, like [ellipsis](https://www.npmjs.com/package/postcss-ellipsis) helpers and [autoprefixers](https://www.npmjs.com/package/gulp-autoprefixer), so this will be very interesting to stay researching about!

#### 1.2.7.3. JS

In one of our first weeks in this course, we've learned about ES6 to enhance our JavaScript skills to the modern standards. Although this could be sometimes tricky for support old / non green browsers, there was a solution for this: namely Babel.

After investigating about CSS gulp tasks, I became interested to see if there was anything build for implementing Babel into my gulp flow. From here I've added Babel with the same sourcemap pipelines to some of my projects. An interesting extra I've learned from here was concatenating multiple files into one, to save HTTP requests with one minified file.

#### 1.2.7.4. BrowserSync

By going through more and more research about build tools, I discovered [BrowserSync](https://browsersync.io/) by accident. BrowserSync intrigued me to research more about it, as the tool offered automatisation for browser previewing with even PHP systems, across multiple devices!

I've tried this out past midnight and got my WIP for Product Lab on localhost working across my whole home network and my WiFi. I couldn't get the live reload working yet for my files, but I was simply stunned by streaming my localhost across my network.

#### 1.2.7.5. Beyond

To keep improving my knowledge about build tools I've been searching a lot of blogs and social media channels to follow writing about CSS, JS and build tools, so I can keep learning new and interesting tools to improve my work flow.

### 1.2.8. Project Building

To help both the development and deployment of Node focussed apps, I've learned to use the NPM config package. This package easily allows you to create configurations in either JSON or YAML. Although we've learned a bit about YAML during our first Drupal lessons, I've chosen for the JSON format for this class.

As a result, instead of being required to update your MongoDB connection, Node is now being automated to switch between either the local or remote MongoDB.

### 1.2.9. Kweeni Team

Together with Sara Breugelmans and Midas Van Espen I've teamed up in the last months to re-create Kweeni. For this project we've bundled our skills from this semester in NodeJS, ExpressJS, ECS6, MongoDB and more to go the extra mile and beyond for finishing this boss task in the end!

#### 1.2.9.1. "Routes"

- [Github repository](https://github.com/laurensdelombaert/kweeni__team8)
- [Heroku app](https://kweeni-team8-dev.herokuapp.com/)

## 1.3. MongoDB University

Paragraphs in this section are copied from the official Syllabus from MongoDB University to better display the topics I've learned each week.

### 1.3.1. M001

#### 1.3.1.1. Chapter 1: Introduction

Introduction to MongoDB, Compass, and Basic Queries

![Printscreen Mongo University](http://laurenk170.170.axc.nl/webtech/m001-lab1.png)

#### 1.3.1.2. Chapter 2: The MongoDB Query Language + Atlas

![Printscreen Mongo University](http://laurenk170.170.axc.nl/webtech/m001-lab2.png)

### 1.3.2. M101JS

#### 1.3.2.1. Week 1: Introduction

Introduction to MongoDB and the Node.js driver; Installing MongoDB; Installing Node.js and using NPM; Introduction to the Mongo Shell, JSON, BSON, and the MongoDB query language; Introduction to building web applications using Express

![Printscreen Mongo University](http://laurenk170.170.axc.nl/webtech/mongo1.png)

#### 1.3.2.2. Week 2: CRUD

Mongo Shell, Query Operators, Update Operators and a Few Commands

![Printscreen Mongo University](http://laurenk170.170.axc.nl/webtech/mongo2.png)

#### 1.3.2.3. Week 3: The Node.js Driver

Deeper dive on the Node.js driver; CRUD operations in the driver; Cursors; writing applications in the driver

![Printscreen Mongo University](http://laurenk170.170.axc.nl/webtech/mongo3.png)

#### 1.3.2.4. Week 4: Schema Design

Patterns, Case Studies & Tradeoffs

![Printscreen Mongo University](http://laurenk170.170.axc.nl/webtech/mongo4.png)

#### 1.3.2.5. Week 5: Indexes and Performance

Using Indexes, Monitoring And Understanding Performance. Performance In Sharded Environments

![Printscreen Mongo University](http://laurenk170.170.axc.nl/webtech/mongo5.png)

#### 1.3.2.6. Week 6: The Aggregation Framework

The aggregation pipeline; pipeline stages; expressions; accumulators, and best practices

![Printscreen Mongo University](http://laurenk170.170.axc.nl/webtech/mongo6.png)