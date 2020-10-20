Gamedoora
=========

### How to Contribute to Gamedoora

Introduction
------------

Welcome contributors, it is great to see your passion, enthusiasm and commitment to build the next level collaborate platform exclusive for the entertainment space. For many years the studios building games, movies or any animation has worked in a close source model, we want to change the way and make the industry an open and collaborative one with building a platform that anyone and everyone can create, connect and collaborate to make there dreams come alive. The concept was born with a desire to eliminate the pain points associated with the current game production pipeline for indie game developers, publishers, large game studios including each and everyone associated with creative industry

Let’s make Gamedoora the exclusive cloud based collaborative platform for game/animation studios and anyone involved in game/animation/film production pipeline.Let’s build with an aim to improve the full production pipeline and help passionate creative enthusiast find and build great new content / games via the community in an open source manner. Think of it as a digital community for the modern and old age mind-sets. "This generation wants flexibility," "There is a need in the community for a place to come and collaborate freely, just like any other open source project (eg Linux, Firefox, Blender, Godot etc)”

Ground Rules & Expectations
---------------------------

Before we get started, here are a few things we expect from you (and that you should expect from others):

*   Be kind and thoughtful in your conversations around this project. We all come from different backgrounds and projects, which means we likely have different perspectives on "how open source is done." Try to listen to others rather than convince them that your way is correct.
*   By participating in this project, you agree to abide by its terms.
*   If you open a pull request, please ensure that your contribution passes all tests. If there are test failures, you will need to address them before we can merge your contribution.
*   When adding content, please consider if it is widely valuable. Please don't add references or links to things you or your employer have created as others will do so if they appreciate it.

How to contribute
-----------------

If you'd like to contribute, start by searching through the issues and pull requests to see whether someone else has raised a similar idea or question. If you don't see your idea listed, and you think it fits into the goals of this guide, do one of the following:

*   If your contribution is minor, such as a typo fix, open a pull request.
*   If your contribution is major, such as a new guide, start by opening an issue first. That way, other people can weigh in on the discussion before you do any work.

Style guide
-----------

If you're writing content, see the following style guides as per the project you are working on:
* Ruby: Refer any of the below guides
  1. https://github.com/airbnb/ruby
  2. https://github.com/rubocop-hq/ruby-style-guide

* Rails: https://github.com/rubocop-hq/rails-style-guide

* React: https://github.com/airbnb/javascript/tree/master/react

* Javascript: https://google.github.io/styleguide/jsguide.html

* HTML/CSS: https://google.github.io/styleguide/htmlcssguide.html

* Java: https://google.github.io/styleguide/javaguide.html

Repositories
------------

* API Repository  
  *  Description It's core purpose is to serve the Public API's which will be majorly consumed by frontend applications
  *  URL [https://github.com/gamedoora/gamedoora-backend](https://github.com/gamedoora/gamedoora-backend)
  *  Ruby on Rails API Framework

* Frontend Repository  
  *  Description Frontend web application for user/admin
  *  URL [](https://github.com/gamedoora/gamedoora-ui) [https://github.com/gamedoora/gamedoora-ui](https://github.com/gamedoora/gamedoora-ui)
  *  React Based

* Incubator Repository  
  *  Description It is a docker application which will let all the application run on docker without local machine config dependency
  *  URL [https://github.com/gamedoora/incubator](https://github.com/gamedoora/incubator)
  *  Docker

* Gamedoora Services Repository    
  * Description It is totally Java Based micro-service, which will be used to interact with third party APIs and RoR API application
  * Repo URL [https://github.com/gamedoora/gamedoora-services](https://github.com/gamedoora/gamedoora-services)
  * Java Based

Contributors have to fork the repo and raise merge requests as per the features/tasks they work on.

Common Pointers
---------------

* Did you find a bug?     
  *  Do not open up a GitLab issue if the bug is a security vulnerability in Rails, and instead to refer to our practice to raise the issue
  *  Ensure the bug was not already reported by searching on gitlab under Issues.
  *  If you're unable to find an open issue addressing the problem, open a new one. Be sure to include a title and clear description, as much relevant information as possible, and a code sample or an executable test case demonstrating the expected behavior that is not occurring.
  *  If possible, use the relevant bug report templates to create the issue. Simply copy the content of the appropriate template into a .rb file, make the necessary changes to demonstrate the issue, and paste the content into the issue description

* Did you write a patch that fixes a bug?    
  *  Open a new GitLab pull request for particular repo with the patch.
  *  Ensure the PR description clearly describes the problem and solution. Include the relevant issue number if applicable.
  *  Before submitting, please read the Contributing to Gamedoora guide to know more about coding conventions and benchmarks.

* Did you fix whitespace, format code, or make a purely cosmetic patch?
  * Gamedoora will generally not accept the changes that are cosmetic in nature and do not add anything substantial to the stability, functionality or testability of Gamedoora.

Setting up your environment
---------------------------

* Getting the repo
  *  Login with github account
  *  Fork the repo to your personal project space
  *  Clone the forked repo to your local system

* Getting the docker
  *  This application is docker based, so prerequisite is to have docker and docker compose
  *  This application is using docker version 19.03.2 and docker-compose version 1.24.1

* Building, and developing
  *  After cloning the repos, make sure all your folders are at the same level of directory.
  *  Toggle to docker application “incubator” through terminal and follow the below steps to run the application
     * docker-compose build
     * docker-compose up -d

  *  For more details about it’s repository, one can go through the respective README files which contain project specific details.

Our Responsibilities
--------------------

Project maintainers are responsible for clarifying the standards of acceptable behavior and are expected to take appropriate and fair corrective action in response to any instances of unacceptable behavior.

Project maintainers have the right and responsibility to remove, edit, or reject comments, commits, code, wiki edits, issues, and other contributions that are not aligned to this guide or our code of conduct, or to ban temporarily or permanently any contributor for other behaviors that they deem inappropriate, threatening, offensive, or harmful.

Our Standards
-------------

Examples of behavior that contributes to creating a positive environment include:

*   Using welcoming and inclusive language
*   Being respectful of differing viewpoints and experiences
*   Gracefully accepting constructive criticism
*   Focusing on what is best for the community
*   Showing empathy towards other community members

Examples of unacceptable behavior by participants include:

*   The use of sexualized language or imagery and unwelcome sexual attention or advances
*   Trolling, insulting/derogatory comments, and personal or political attacks
*   Public or private harassment
*   Publishing others' private information, such as a physical or electronic address, without explicit permission
*   Other conduct which could reasonably be considered inappropriate in a professional setting

Community
---------

*   Discussions about the Gamedoora take place on Gamdoora GitLab Issue Board and Pull Requests sections. Please can request to join and start contributing.
*   Wherever possible, do not take these conversations to private channels, including contacting the maintainers directly. Keeping communication public means everybody can benefit and learn from the conversation.

Gamedoora is a volunteer effort. We encourage you to pitch in and join the team!
