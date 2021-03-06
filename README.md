# <img src="https://cloud.githubusercontent.com/assets/7833470/10423298/ea833a68-7079-11e5-84f8-0a925ab96893.png" width="60">

# WILD WILD KANYE WEST - tunely lab


"I feel that if I had more resources, I could help more people. I have ideas that can make the human race's existence within our hundred years better." - Kanye West

![alt text](https://media.giphy.com/media/3oEjHIxD6j01Q8ZWbm/giphy.gif "Kanye")


Kanye has ideas, but he needs more resources!! That's where you come in. We all know people only use 20% of their brain, but kanye uses 100%.
He needs the space in his brain that he’s currently using to remember the worlds greatest album collection (kanye’s own collection) so he can solve cancer. or something.
Kanye needs a single page web app to list all of the albums in his collection and a way to add more when he drops new ones.
If you accomplish this task, I'm told he will "love you like Kanye loves Kanye"... which as we know... is a lot.


Full stack JavaScript Application.

Prerequisites:
* jQuery, AJAX
* Express server, static assets
* RESTful design
* JSON serving /api routes
* Bootstrap - the lab will introduce modals
* CRUD with mongoose
  * mongoose embedded relationships
  * Part 3: mongoose references

## Overview

This lab begins with a basic front-end to display a list of music albums.  As we progress through we'll:
* serve the album data from our server's `/api/` routes.
* get the data from the server using ajax and display it on the page with jQuery
* retrieve the data from the database
* add functionality to create a new album
* add functionality to remove/delete an album
* add the ability to edit/update an album
* support storing song information (with full CRUD) (mongoose embedded)
* add a second major route for artist information  (mongoose reference)


### Project Planning

It's important to do a good amount of planning and whiteboarding before you start coding.  That'll save you from costly mistakes and help you to refine the eventual user experience before you've invested hours in the project.

We're going to use **"outside-in development"** practices.  This means that we'll start by designing our UI (the outside).
Then we'll move more inside by connecting it to a backend serving hard-coded data.  Next, we'll retrieve that data from a database.

We will also be breaking our work into short **sprints** with specific design goals.  In each sprint we'll try to work outside-in.  

Let's start with a basic wireframe.  

![Image Alt](docs/assets/images/tunely_wireframe-1.png)

Typically when you work on a project you'll start with a basic idea and do your initial development on paper or whiteboard.  You can develop and "virtually" test your app with wireframes.  There are also a number of software packages that will help you build wireframes.

In the above you can see we're building a site that displays a list of musical albums.  It also has a jumbotron to introduce users to the page.  This is our starting point only; you'll be responsible for evolving it as we work through the lab.


## Getting Started

* fork and clone this lab repo
* read this doc then proceed to sprint 1


## Sprints

### Module A: Create and Read with Mongo and embedded model relationships.

#### Sprint 1

[Sprint 1: serve & display hard-coded data on the page, then connect to a database](/docs/sprint1.md)

#### Sprint 2

[Sprint 2: add a form and support creation of new data](/docs/sprint2.md)

#### Sprint 3

[Sprint 3: add mongo embedded song data](/docs/sprint3.md)


### Module B: Update and Delete with Mongo and embedded model relationships.

#### Sprint 4

[Sprint 4: delete albums](/docs/sprint4.md)

#### Sprint 5

[Sprint 5: edit and update album info](/docs/sprint5.md)

#### Sprint 6

[Sprint 6: update song info & delete songs](/docs/sprint6.md)


### Module C: Full CRUD with Mongo and reference relationships.


## Licensing
All content is licensed under a CC­BY­NC­SA 4.0 license.
All software code is licensed under GNU GPLv3. For commercial use or alternative licensing, please contact legal@ga.co.