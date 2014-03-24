---
tags: project, meta
language: ruby
---

# So you're starting a Ruby on Rails project at Flatiron School

## Introduction and Objectives

The last few weeks of the Flatiron Ruby semester includes a project mode where students get to work on building real applications. The goal of this period is to expose students to actual problems that arise when building and teach them how to manage a project. The goal of the projects is not to launch a massively popular social network or startup, but rather, just to learn.

    Education is an admirable thing, but it is well to remember from time to time that nothing that is worth knowing can be taught.
    - Oscar Wilde

While we love teaching you all the things about programming, in the end, we're trying to build things, and that isn't something we believe can be taught, but rather, must be learned by trying and failing and exploring.

So make sure you are keeping your eye on learning, a constant balance between building and shipping and learning.

During project mode, our expectation of you is that you ship at least 2 small projects.

**TL;DR**
* Expose students to actual problems
* Learn to manage projects
* Goal is to learn, not build a company
* Learn though building things
* Ship at least two small projects

## Working in Teams

During project mode we want you working in teams of 2 to 3 people. Do not work alone, that is absolutely not allowed, and do not work in teams bigger than 3, they are hard to manage and add a people layer of complexity to the project.

We believe that as professionals, you should be able to, in fact take pride in your ability to, work with anyone. Work with people more advanced and less advanced and figure out how to be productive in both situations. Work with people that share your interests and people with wildly diverse backgrounds and figure out how to leverage all perspectives.

So who you work with shouldn't matter, but it does. Try to pick people that share your goals of learning and your values as a developer, the pace and hours you want to keep and the technologies you want to learn, and the problem you are looking to solve. It should be fun.

**TL;DR**
* Teams of 2 - 3 only
* **Do not work alone!**
* Should be able to work with anyone
* Pick partners with varying backgrounds
* work on your weaknesses
* Work with people interested in working on the same project
* Have fun

# Picking a Project

Building something usable is tremendously hard. There are a few things we've learned over the years about building.

1. Everything is harder than it sounds. You'd be surprised how quickly complexity grows. Be humble about your estimates and somewhat realistic about what you can accomplish.
2. Keep it simple! Seriously, embrace constraints. Make your project as small as possible while still capable of delivering the majority of the value. Maybe you don't need a User registration system that supports 10 external OAuth providers, maybe you don't need to allow them to reset their passwords (do you even have users complaining about this?), maybe exporting to PDF is enough and you don't need to support epub and kindle. Just keep it simple. 1 version of something is more than enough. Think Minimum Loveable Project.

Beginners have a tendency of choosing very hard projects, pick a project that you can imagine having a somewhat working version of after a day. Keep it simple and small.

We love projects that utilize external APIs and Data Sources. They make everything more interesting.

- [Github](http://developer.github.com/v3/)
- [Twilio](http://twilio.com)
- [Wit.AI](http://wit.ai)
- [Facebook](https://developers.facebook.com/)
- [Twitter](https://developer.twitter.com)
- [NYC Open Data](https://nycopendata.socrata.com/)

In terms of what projects are cool, we tend to think the nature of value in software lies in being able to answer or automate a question that was previously difficult. For example, Airbnb answers the questions "Who's couch can I crash on tonight?", Kickstarter "Where can I get money for an art project?" (or conversely, "Which independent projects can I support?"). Your application, every feature, should answer a person's question. For instance, an application you could build might answer "Who is committing code at Flatiron School right now?", "Who wants to meet for tutoring this weekend?". Focus on questions, on problems, then solve them with code. Your application should answer at most 2-3 fundemental questions.

You can find more ideas here: https://gist.github.com/aviflombaum/616c9841a9af68cf0eb0

And see past projects here: TODO

Once you have a team and a project, sign up here: https://docs.google.com/forms/d/1ctwqhTTMm3EUYsBE8QwtOmpEyXdc1CbpcdapdiXpM0g/edit?usp=sharing

**TL;DR**
* Be humble about your estimates
* Keep it simple ( Minimum Lovable Product)
* Should have a working version after a day
* External APIs make projects more interesting
* Think about answering or automating a question

# Starting Your Project

* Clone from the Flatiron [Template]()
  * The template is just an empty rails project with basics like Bootstrap and
  Google Analytics installed already.
* Setup external services (API's, etc.)
* Get a base layout done
* deploy a homepage

# Planning and Working on Your Project

1. Iterate! Stay fast and small. Build things in small parts. You should be able to launch a new feature every day because you build in the smallest possible unit and are constantly driving toward deploying a new piece of code. Don't pile up requirements, look for shortcuts, look for ways of having a 'good enough' version of the feature and not all the bells and whistles.
2. Make videos. Every day you should make a short, less than 5 minute video that
demonstrates a feature you built today. The point of making the videos is to
keep you focused on delivering features, and prevent you from wasting time in the
wrong areas.
3. Dont' get bogged down by complexity. focus on the the smallest unit of work,
and build up from there. Don't spend time planning
every detail of your project. Get an idea of what you want to build and start.
You shouldn't find yourself designing a schema with a dozen tables. You also
shouldn't find yourself mocking up all the pages of the app before you've written
a line of code.
4. Deploy! You should deploy something on the first day, and every day after that.

#####Frameworks and Huge gems
Don't JS frameworks or big gems like:
* ActiveAdmin
* RefineryCMS
* Backbone
* Angular
* Ember

**TL;DR**
* Iterate!
* Launch a new feature every day
* Make it good enough, not perfect
* Make < 5 minute video every day to demonstrate a feature you built that day
* Deploy on day one

# Working with Your TAs
1. Work with one TA. Your project will get complex, so you'll be working
with the same TA until you're finished. This will make the TAs more familiar with
your project, and a lot more helpful.
2. Don't let yourself get stuck. Your TAs are here to help you. Use them when you
get stuck. You want to make consistent progress. Don't spend the day stuck on
something.

**TL;DR**
* Work with one TA
* Don't get stuck
* Use your TA

# Standups
Every morning meet with your group, stand up and have each person tell the group
what they worked on the previous day, what they had trouble with, and what they
are going to work on today. Keep it short and focused.

**TL;DR**
* Have a daily standup

# Edge Lectures
Every day at lunch there will be Edge Lectures on topics that aren't necessarily
important for everyone to attend. They will cover interesting gems, Image
manipulation, writing responsive html/css, Mulit Step AJAX, and other topics that
are interesting to a subset of the class.

**TL;DR**
* Daily lectures on interesting topics

# Schedule During Project Mode
You'll have a lot of free time during project mode to work on your projects. Most
days, the schedule will look like this:

Time          | Objective
--------------|-----------------------------------
9:00  - 10:00 | Standups
10:00 - 12:00 | Working on projects
12:00 - 1:00  | Lunch and Edge lectures
1:00  - 5:00  | Working on projects
5:00  - 5:30  | Prep for Retro
5:30  - 6:00  | Retro ( 4 groups, 5 minutes each)
