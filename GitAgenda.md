## Git Course Agenda, including some explanations

### Section 0: Introduction

This section covers the "thinking of git". You will learn how it all came about, and where it came from. We cover how git is meant to be used, and what differs from other version control systems. Using Git is also a change of culture, and we discuss this, and will push you to see if something needs to be changed in your company based on this. 

We will walk through the internals of git, and how it is built up. Then we will show the basic elements of a git system, and how these elements fit together. You will learn about the concepts of distributed version control, and why that works. You will learn how git appears on your local machine, and how it works with respect to the remote. 

We will then move on to remote storage options. The course will later go into details on some of the possible options you have, but we have a special focus on GitHub and Azure DevOps. We will also touch upon the options you have for creating large git repositories. You will learn that git repositories should be small and why that should be so, but you will also learn when and how to break that rule. 

The last one up on the introduction is the client tools you can use. In this section we will go through the different options you have. The participants will ensure that they have the necessary tools installed, including some special tools for the course (and also very useful afterwards). If the participants have installed all tools upfront (they will get a list), we will just ensure they are all working as they should. 

Expected time is 1 hour. 

### What are the Levels

The levels define both the maturity you have or want. If you have very basic needs, you don't need to go to any of the higher levels. Regardless of where you're going, you can always start working on lower levels. 

We have a [very good definition of the levels available](https://terjesandstrom.github.io/GitScenarios), these also have some posts that describe what you do on each level. You can read through these to establish of you feel you master this level, and then, if you are in process of having an in-company training, decide what levels you can go easy on, and which you need a more deep training.

These levels are from the developers perspective. From a DevOps perspective you may have have further needs, that we will address in separate sections.

If you are a company, you most probably need to be be on Level 4. You will also need to determine how your company will handle a git system. The course has a separate section on maintaining a git system in a company. 

### Section 1: Level 1 - the basics

This section concentrates on the basic Git operations. There are not many of them, and with this knowledge you can do useful work with a git repository connected to a remote storage. 

You will learn how to create a Git repository, and how to connect it to a remote. You will learn how to do all operations to both add to it, edit information and retrieve information. 

During this section you will be introduced to the different local git issues, like staging and indexes. 

You might have noticed that this information is actually hosted in a git repository. With the knowledge from this section, you can do the same! And the objective of this section is to actually do that, and place your notes from the course in your own similar git repository! 

Option 1: If the participants have never used git before, we will spend some extra time (up to 1 hour) to work through this more slowly.

Option 2: If the participants comes from TFS VC we will work through some of the differences in the operations between these two systems. Expected time 30 mins.

This section is relatively easy, and we don't spend too much time here. Expected time is 1 hour. 

### Section 2: Level 2 - Branching and merging, and creating a readable history using tags

This section is meant to raise your level to where you can safely work with other people on the same repository. To do that you need to understand and handle branching. Branching in git is very different from other systems, and is essential to have a good git experience. We focus on understanding what branches are, and how they actually work, and also why they are so extremely low-cost in git. 

We also cover the theory of branching, and what kind of branching policies you should promote in your work, with your team and in your company.

You will learn how to branch, and the differences and similarities between local and remote branches. This will be connected with what you learned in Section 1, about how branches works with repository synchronization with the remote.

Merging is a fundamental piece of branching, and as git have different types of merging we will work through these both in theory and in practice. We will show how you can use conventions to make your branches more easily to handle, and how tools are actually supporting some of these conventions. 

You will also learn how branches can easily be visualized in the recommended tools, and how you should visualize it yourself! It is different! 

Tags in git are a sibling of branches, and you will learn how they work and for what purpose. You will understand how it can help you to create a more readable history. You will also learn how to convert between these. 

The exercises you do will be best experienced using the teams we have divided the participants into. You will need to collaborate with your team friends, and together ensure you can work effectively using branches. 

Expected time: 2 hours

Option 1: Connecting git branches up to work items/issues (30 mins to 1 hour)

Option 2: Deep dive into trunk based development (30 mins to 1 hour)

Option 3: Help! I am drowning in branches! How to maintain? (30 minutes)

### Section 3: Protecting master and using Pull Requests 

Pull Requests are about how to protect your master branch. In order to ensure you have a working and "green" master, you need to use Pull Requests. We will work through how you work with pull requests, and (DevOps) how you set up Pull Request policies, which is what actually creates that insurance. To set up the policies we will do that using one of the two preferred systems (GitHub and/or Azure DevOps)(companies in-house training can choose).

In this section we will set up a simple CI build to be used with the Pull Request policy. If this is unknown to you, we will ensure it is in place for you, so you don't need to spend any time on it. 

You will learn how to create pull requests, and how to work with them. There are different ways of how to handle them, and your team (or company) have to agree on what to choose.

When you're closing Pull Request you have some choices on how to do that. We will work through the different options and what they're essential meanings. This will ensure you know when to use what, and what the consequences of each are. 

The part on establishing a policy in this section is essential for DevOps engineers.

Expected time: 1 hour

### Section 3b: Rebasing

This is a practice which is relevant in two situations, locally when you pull down from a remote, and remote when you merge a branch. You will learn what it is, how you execute it, and also the dangers of wrongly done rebasing. 

Rebasing is a concept that is often hard to understand, so we will spend some time on getting this clear.

Expected time: 30 mins to 1 hour

### Section 4: Cleaning up Git mess

When you're working, you will at one time or another get into complex situations, and you will from time to time do something that makes a sort of mess out of your git system. 

Git mess can be very light, and it can be more complex. In any case, it does no real harm. It is fully doable to fix up nearly anything in git. 

In this section you will first learn the most basic cleanup mechanisms, which also are applicable on Level 1, and the more complex ways of cleaning up git.

You will learn how to fix issues that have messed up your remote repository, which are the most serious ones, and the more easy ones which only affect your own repository. We will be using a flowchart for selecting the approach you should take, and based on that you will do exercises on repositories that are severely broken! 

You will also break your own repositories in different ways, and work on everything from very simple fixes to the "how did we get here" type of things.

Parts of this section is very hard, using some very complex git tools. It may not be necessary for everyone in a company to know these parts, but there should at least be some in a company that have this knowledge. 

This section is essential when you're working with multiple people and also when you are a DevOps engineer with responsibility for the remote storage for your company.

Expected time: 2 hours

### From levels to expansions

These 5 sections will be the fundamentals you need to survive with git. In the following sections we will expand on that knowledge and broaden the knowledge of git. These sections can be taken from any other section after section 2. 

These expansion sections can be options if you have a company in-house training, although we recommend that you should at least visit the sections, even if you don't do a deep dive with full exercises on all of them.

Git is both simple and complex. It is simple to use, and extremely robust. It is complex with respect to the many things you can do with it. We will show how you can cope with that complexity in the following sections.

Each of the following sections can take from 30 mins to 1 hour.

### Section 5: Git history, blame tools and branches wherever you like

There are several ways to view a git history, and you will learn how the different tools can be used for this purpose, and also how you can find things in a git repository. Included here is the use of the so-called blame tools, answering your questions on "Who did THIS?". Not that you really should know......

The git history is not only a read only log. You can use the history to go back and create branches. You will also be introduced to working outside branches.

### Section 6: Configuring Git, including aliasing

Git can be configured in many respects, and we will work through the essentials of this. We will show how you can add aliases to git to make it easier to use.

Essential here is that you learn the consequences of wrong configurations, and how that can affect anybody's experience with your git system.

### Section 7: Managing git repositories

After a while you as a person will have many repositories. A company will for certain have multiple. There are ways to organize them, and you will learn how you can do that in a way that inflicts minimal pain. 

You will learn how you can figure out details of your repositories, and in cases where you need to change something with respect to your repository, you will learn different ways of doing that. 

You will also learn practices for backing up git repositories, and how to work whe disasters happens (remote storage down). Among those practices are how you can set up your own folder based git remotes. 

### Section 8: Working with multiple remote repositories

(Recommended) There are multiple situations that will make it essential to be able to use multiple remote repositories. This knowledge also makes it easier to understand the distributed nature of git. 

You will learn how to configure this, and how to create a structure to make this manageable.

### Section 9: Working with non-owned remote repositories, aka forking. 

You need this knowledge if you a) are contributing to other peoples open source projects b) are having an inner-source culture in your company and want to contribute to another team's repository.

It is easy to create your own fork of another repository. You will learn how to keep it in sync, and how to contribute back to the source repository in a manner that avoids [Git Mess](#Section-4-Cleaning-up-Git-mess). 


