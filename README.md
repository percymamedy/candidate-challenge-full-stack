# Full Stack Candidate Challenge Project
## INTRODUCTION

Ringier South Africa serves as one of two tech hubs for Ringier's global operations. We build marketplace systems & Websites and fulfill a role to further the technical excellence for all of Ringier's many interests.

Our marketplace plaforms are made up of Cars, Jobs, Property and General Classified assets; uniquely localised and expertly scaled for markets on multiple continents.

This challenge project will give you a glimpse into life as a developer at Ringier South Africa.

## WHAT ARE WE LOOKING FOR?

We're aiming to understand where you're at as a Full Stack Developer. We do not expect a production ready app, just enough for you to feel like you've communicated your level of skill to us.

We expect that this should take between 3-8 hours to complete, with at least another hour per bonus feature that you tackle. The idea that this is a big sacrifice of time is not lost on us! It's no small ask, but we find it important for the following reasons:

1. To give you time to decide if this is a product space that you could get excited about.
1. For us to be able to honestly evaluate your competence, style and approach for the job at hand.
1. For you to be forced to play with some of our unique stack. Especially *Tailwind CSS*, which really needs to be experienced rather than explained.

We will rate the delivered work based on the expected position level as follows:

### Junior Level
* A working project is nice, but not the most important thing
* *Tailwind CSS* should be used to enable a responsive design and to style the UI. This is actually very important, so don't choose a different CSS framework
* The Javascript framework is used in such a way that it displays a good understanding of how Single Page Applications work
* The back end is architected in an understandable and maintainable way
* Include a Readme text file with any installation instructions you feel we need. Also add details for anything you found hard or confusing for this assessment

### Middle Level
* A working project
* Tailwind CSS should be used correctly to enable a responsive design and to style the UI into something decent
* The Javascript framework is used in such a way that it displays a good understanding of how Single Page Applications work
* The back end is architected in an understandable and maintainable way
* Was testing considered and tried?
* Include a Readme text file with any installation instructions you feel we need

### Senior Level
* A working project
* The front end build setup shows a good understanding of how to configure a modern Javascript framework and *Tailwind CSS* for development and production
* Tailwind CSS should be used correctly to enable a responsive design and to style the UI into something decent
* The Javascript framework is implemented as expected to produce a functional front end
* The back end is configured such that the basics for a new system are set up correctly
* The back end is architected in an understandable and maintainable way using up to date framework techniques
* Tests are expected, however, there does not need to be full coverage. It should be clear from the tests that are written that testing was planned
* Include a Readme text file with any installation instructions and other notes you feel we need
* Implementing extra features is a signal of planning well and of the ability to execute quickly

## THE CHALLENGE

Get into the head-space of buying or selling on your favourite marketplace plaform (e.g. Lexpress Property in MU, or Gumtree if you're in SA), and build us a basic marketplace POC. These are the main features we're after:

1. A Listing Search Page (which could also be the Home / Landing Page)
1. A Listing Detail Page. (Showing more info on a single Listing, refer to list at the end of the readme)
1. A Create Listing Page

## CRITICAL PROBLEM STATEMENT

Generally most marketplace platform like the one you will be developing are usually publicly available and attracts lots of attentions from bots and website crawlers. The unintended consequences of this visibility is characterised by an unusual 
spike in your overall website traffic and sessions. Given this possibility, your POC needs to be optimized for performance, scalable and able to withstand an unusual increase in traffic. 
It is our expectations that you use this opportunity to demonstrate your ability to integrate tools and services that can help structure your POC in such a way that it can sustainably handle these challenges while delivering your business core values.


In Addition, we ask that you choose at least one bonus feature below to implement.  (You can definitely pick more than one if you're on a roll, or if you'd like to show off some of your other skills!)

### BONUS FEATURES:
* Use [Laravel Livewire](https://laravel-livewire.com) for some of the pages. You decide which pages would benefit the most
* Sign Up / Sign In Pages for User Creation. Go one step further by adding the ability to log in via an OAuth provider
* Add Auth onto the Listing Create Page
* Extend the search to add Filtering for Price. Extra points for pagination and sorting
* Add Images onto Listings, including Image upload
* Implement PurgeCSS (this is expected for the senior level assessment)
* Docker / docker-compose Setup
* Automated Tests

## WHAT IS EXPECTED IN YOUR TOOLBELT?
* A Modern Front End Framework: VueJS, ReactJS, Angular or Alpine & Livewire
* Performance oriented architecture and design (Tools and services necessary to optimise the application)
* [Tailwind CSS](https://tailwindcss.com/) (We'd really like you to give it a try)
* [Laravel Framework](https://laravel.com) for the backend. You can use anything for the DB. Please include migrations and seed data
* Github (or Bitbucket/Gitlab if you must!)

### INSTRUCTIONS
1. Commit often, with meaningful commits. We'd rather see real commit history than it all magically coming together. Please start with one initial commit after starting with any framework / bootstrap code so that we can clearly distinguish where the community code ends and your code begins.

1. Complete at least the basic features plus 1 bonus feature.

1. This is a Full Stack challenge. We expect to see the best practices for both front and back end development. Depending on your chosen technologies, these include things like:
    * Adherance to community guidelines, standards and best practices
    * Component Driven Development
    * Routing
    * State Management
    * Clean Validation of all inputs
    * Functional Components
    * A clear, concise readme file with full setup instructions.

1. *Use Tailwind for CSS.* We know you probably have never touched it before, but now's a great time to get your feet wet and be exposed to something new!  We will not be too opinionated on implementing a specific design. You're welcome to just replicate a marketplace platform that already exists or just free-style it yourself. We won't expect it to be perfect, but it should be clean, simple and work on mobile (Mobile First)
Remember, this is a development challenge, not a design challenge!

1. Once you're done, please drop us a link to your repo.

1. We ask that you get this submitted within 1 to 2 weeks of receiving the challenge. If you need further time, just drop us a message and let us know.


That's it. If you're stuck with any of the above, or would like further resources on Tailwind CSS please reach out. We're on ZATech Slack or Email.

Here's a list of the minimum fields that we'll be looking for on Listings
   * Title
   * Slug
   * Description
   * Date Online
   * Date Offline
   * Price
   * Currency
   * Contact Details (Mobile and Email)
   * Category (One of the following)
       * Furniture
       * Electronics
       * Cars
       * Property

And search should have at least the following features.
 * Search by string matching in title
 * Search by category
