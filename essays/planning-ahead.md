---
layout: essay
type: essay
title: Planning Ahead and How I Learned to Love Github
# All dates must be YYYY-MM-DD format!
date: 2020-05-14
labels:
  - Configuration Management
  - Github
  - Agile Project Management
  - Issue Driven Project Management
---

## So Much To Choose From

There's so much I learned from ICS 314, meaning there's so many choices to pick from in writing about the experiences I've had and the lessons I've learned.

The multitude of new shortcuts and options in coding with javascript and the different frameworks that allow you to do a lot more with a lot less.

The different processes and interactions that go into building a respectable framework and making sure that what you build upon that and what you take away from it are well thought out.

Instead, I decided to go with something a little less code-centric, but something that I'll take away from this class and put towards future projects, computer class or otherwise, well into the future.

I'd like to talk about configuration management and agile project management and how they've changed my perspective on group projects.

## Branching out

<img class="ui medium center floated image" src="../images/branches.jpg">

Configuration management and open source development have been eye opening to me throughout this course. Configuration management being a more broad term that covers the development of a project in respect to its ability to keep consistency and maintain integrity of the project throughout the entire development process. Open source development is somewhat self explanatory. Instead of keeping the code under wraps and developing it within your group or organization, you make it free to be distributed, copied, scrutinized, and changed by the public. While there can be reasons to avoid this, the advantages of sharing and allowing your testing team to potentially be the entirety of the internet make it very lucrative when you only have so many resources to work with. Being able to share, collaborate, and even learn from other users from all over can mean catching or fixing those random bugs and surprises you would have otherwise missed.

This is where Github comes in. While I had heard of and knew of the site before taking ICS314, I had never had a reason to delve into it before. Having experienced its features first hand, I can vouch for it's ability to collaborate and plan projects with a lot more control than I had ever imagined.

### Repositories

The first concept to understand is having an individual repository as well as an origin repository. Repositories are like the container for your project's files. Being able to clone your own version of the repository, or repo, means you have access to your own self-contained copy to do with as you please. Break the code, fix it, modify it, or add things and none of it affects the original until you push that information to the origin repo. As long as you're paying attention and being cautious, this means you always have an undo button without the fear of trying new things and messing up. You can just collect the original repo and clone it back into your individual copy and you're as good as new.

### Branches

The second concept is the master branch and creating branches. Thinking of a tree, the master branch is the base of the tree, its trunk. This is your final product, the thing you're going to present at the end of it all. The branches of the tree, the created branches, are each pieces of the final product that you're trying to test out and make work. A little similarly to the idea of having an individual repository, within your project you can have branches, which are offshoots of the master branch that contain edits and additions to the original, which lets you work on something despite what others may be working on elsewhere within the project.

Lets say you made a project where you needed to make a website for a restaurant. There's going to be multiple pages that need to be made, and not all of them interact with each other. With branches, that means you can have one person working on a menu page, another on an order page, and someone working on the home page all at the same time. If nobody is causing conflicts and editing the same parts of the project, three people are able to get things done without regard for the others.

So now you each have your own individual repositories and you're all working on your own branches away from the original master branch. What are you supposed to do with that branch and how does everyone else get it when they need it?

### Merging, Pushing, and Pulling

Merging branches and pushing/pulling repos are the last pieces of the puzzle. When you're done with a branch, and you've tested it and made sure it works, you can merge one branch into another. Github will take the two branches and push them together, adding any new files, removing the ones that aren't there anymore, and changing the files that have discrepancies. Now on your own individual repo, you can test to make sure that it works with your own master branch. If it does, you can push that master branch back to the origin repo. Now whenever the others access the master branch, they can pull the new copy of the master branch and see the changes you made.

In this way, you have this nice group environment where people have the ability to avoid stepping on each others toes while working on assignments.

How do you keep the team productive while still making sure they "stay in their lane"? For that, we'll need to talk about Agile Project Management.

## Gotta Go Fast

<img class="ui medium center floated image" src="../images/speed-timelapse.jpg">

### Agile Project Management

Agile project management is one of multiple project management methods that combines multiple ideas, but focuses on its ability to get work done faster, but in smaller chunks. With this ability to pinpoint more specific areas, you can get a faster turnaround time on both the reviewing process and fixes to anything that comes up. This does require a good amount of teamwork and collaboration as the constantly flowing production of each section needs to be able to keep moving and build off each other to make the finished product. If there are slowdowns or problems that need to be fixed, you want to be able to pick up the slack and keep the work flow moving. Otherwise you'll come to a halt.

In particular, one type of agile project management is called issue driven project management.

### Issue Driven Project Management 

Issue driven project management focuses specifically on the issues that naturally occur during project development. This method allows you to encounter and resolve problems more naturally and build up a work flow that adds more things, even as other problems get solved. This also can help projects from getting hung up on certain road blocks as if a new issue pops up, someone who may have an idea how to resolve it can take over and that frees up the other person to continue to be productive elsewhere.

This combined with Github make for what I found to be a pretty solid approach to solving problems and completing projects.

## It's All Coming Together

<img class="ui medium center floated image" src="../images/all-coming-together.jpg">

So you've got your branches and repos. Your project management method all ready. But there's even more to Github that makes it go even smoother. Introducing the issue and project features.

### Issues

We've already talked a bit about how issues fit into issue driven project management. Github has a entire section of your project dedicated to creating and cataloguing your issues so that you can easily keep track of them all. Being able to filter and sort them out as well as create templates so everyone can easily follow the same format makes for a nice way to keep things organized. People can comment and respond to each issue, allowing others to keep up with any progress and noteworthy things while working through one. This also allows images to be added if you need to show proof of completion or a way to show examples easily before officially closing an issue. Closing an issue, meaning it shows the issue has been fully resolved, though reopening one is available if something happens. It also allows you to assign yourselves and other group members to an issue so that you know exactly who's working on what. This feature also integrates neatly into projects and milestones.

### Projects

Sure you can keep things organized by checking each individual issue, but with the project section, you're able to fit each issue neatly onto a project board that can keep track of it all for you.

With some of the automated templates, things like moving things from a to-do section of the board, over to the in-progress section is possible. Even automatically moving an issue to the complete section when an issue is closed. Being able to view information about each issue right there on the board, editing that information, and viewing who's working on what makes this a nice tool for getting your project organized and easily trackable. Plus the project board is customizable and you can adjust it and add or remove sections as you see fit.

## Party Of One

<img class="ui medium center floated image" src="../images/party-alone.jpg">

Though this fast paced style of progress is simple and easy to implement, the team really needs to make sure it's able to keep up with each other. Without a team fully behind it, you can run into hiccups that may end up costing time and effort.

Getting frequent feedback and making sure things are progressing smoothly and properly is key. Without having people to check in often, things can slip through the cracks. Without as much proper documentation and formal procedures, you could end up with something that needs to be found, reopened, and dealt with again. Having that extra pair of eyes can help create that safety net that this method of development could leave open.

With how quickly the turnaround time is on each issue, without proper coordination and work being put in, burn out can also be very real and cost more time than it gives. With how simple it is to start a new issue keep working on issue after issue, if one person takes on too much, they may end up less productive, or make more mistakes and get sloppy.

Lastly, but most crucially, following what few guidelines there are is integral to making sure things progress smoothly. Referring to the board, making sure you fill out and keep track of the issues, and properly label everything means the difference between progress and a screeching halt because you thought you were working on something else. As a small addition to this, using some form of tracking system in your system, such as branches to individually work on each issue and ONLY on that issue is a good way to make sure you don't stray too far with your reach in any given problem.

## Outside The Box

<img class="ui medium center floated image" src="../images/outside-the-box.jpg">

Overall this has been such a brand new experience both in working with a team on a proper project and using the various tools available to me to get it done. Even more importantly it gives me both insight and experience into how to handle projects even outside of software development. So much time is saved when you have a system that lets you manage and organize the project as a group. Especially when you're able to break it up piece by piece and work simultaneously to get things done efficiently. It also helped me understand the limitations of these systems and what's required to make sure they work for your project. Taking this mindset into individual projects or other school related ones will help keep it on track.

I'm truly grateful for the opportunity this class has given me to take another step into the world of software development.

