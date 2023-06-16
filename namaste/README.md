## Info

* Code name: Namaste
* Introduction: this project was from the idea to create a platform for film suggestions, not based on user's interests, but try to increase diversity of their consumption. Some other ideas have been added after, we hope this project can work as a platform to carrying related ideas, based on these advanced concepts such as "open access", decentralization, etc.

## Participation Suggestions

* Similar projects or services. Necessity of the project or features.
* Platform and tools for collaboration.
* Ideas: design, features, philosophy, stack, roadmap, etc.

## Discussion
### Centralized or Decentralized

Decentralized are seemingly more promising, but we need to consider:
* best path to our main goals
* disadvantages compare to centralized
* technical viability

#### Status

ongoing 

#### Points

* decentralized
    * possible disadvantages:
        * Decrease collectible data used for research and community buildup.

#### Topics

- [ ] Should the project decentralized at the beginning?
- [ ] Any better ideas on decentralization compare to Fediverse? (Consider the so called "Web 3", and possible financial features in the feature.)

## Design & Features
### Topics

- [ ] Security, animosity
    - [ ] No password
- [ ] How to decide if one item worth recommend or not, and their weight.

### Targets

* data storage & retention, personal & humanity as a whole
* personal enrichment & education
    * decrease information/education inequality
* content: spreed (advertising), distribution, revenue generation and distribution
* social change (not just works as a hard drive or for people's entertainment)

### Philosophy

* simplicity
* decentralization (?)
* complete personal independence and sovereignty, with choice to connect to network when wanted or needed
* Modular parts, for easy implementation to other projects.

### Overview

* Suggest media (films, books, music, etc.) to users.
    * goals:
        * Increase diversity: suggest works from different country, culture, language, time periods, category, etc.
        * Provide suggestion profiles that users can choose from directly, and also detailed customization.
        * Enforce the goals above by setup schedules for example one suggestion per day or per week.
    * group suggestions: provide suggestions based on data of a group of people, for example a couple, a team.
* A people's database own by themselves.
    * Able to import data from other platforms such as Letterboxd, Goodreads.
    * Consumption: watch history, rate, review, etc.
    * User set their data private or public, group or item based.
    * User export all their data.
    * API: export all useful data for external connection.
* New copyright & revenue models. For example:
    * User set their payment goals for consumption, item based or category based (for example: pay $1 to every item watched, or pay $10 to all in films category every month).
        * This works as a way to express gratitude to content creators.
        * Why need this extra way:
            * People may find the price they paid are lower that what they wish to pay.. 
            * People obtained the content from places without payment.
* Better Review Management
    * Category review before post: is it balanced, or from one specified perspective, etc.
* Access
    * Multiple access methods: website, API, email, chat bot, etc.
    * Possible to connect with external platforms, such as library, media server, etc.
* Community
    * Different weight of user reviews based on their reputation, etc.
    * A more scientific voting system: voice weight, etc.
    * Suggestions based on user's reviews, etc., not only external data.
* Distribution
    * Publishing of new content.
* Open source
    * Open sourcing the project as much as possible.
* Retention
    * Guarantee data retention even if main platform destroyed.
        * Maybe 3rd party data backup?
    * Permanent data management
        * Manage data of person afterlife.
* Legal
    * Ensure legal status of the whole project.
    * Ensure legal and reputation boundaries around external connection.

## Roadmap
### Step 1

- [ ] Decentralized? And structure.
- [ ] Basic stack: frond-end, back-end, database.
- [ ] User registration.
- [ ] Film suggestion algorithm: 
    * Skip already suggested;
    * Filter suggestions based on rating;
    * Suggest 1 documentary in every 3;
    * Ensure diversity, different suggestion compare to the last 2 ones on aspects: language, category;
- [ ] Suggest 3 times per week, keep suggests into user's database.
- [ ] Send email of suggestions to user.

### Step X

* User be able to set their name. Either full name, nick name, or no name. If no name, the system generate a lovely name for the user.
* Set consume status of items.
* Import consume data from external platforms.

## Similar Projects
### Database
#### Movie

* Letterboxd
* IMDb

### Recommendation

* TasteDive
* Movielens
* the-syllabus.com

## Tech Stack
### Not

* Meteor.js: needs Node.JS EOL version 14 which does not compatible with some new packages.  (Jun. 15, 2023)