---
title: iPad Workflow for Updating Grav via GitHub
layout: post
---

Through my [day job](http://campusmanitoba.ca/), I'm regularly exposed to innovative work happening in educational technology and open educational resources. Some of the time, a project peaks my curiousity enough that I can't help but dabble in the technology myself. As of late, this led me to installing a CMS called Grav to create an "online course hub" that can be used with GitHub to create an open, collaborative platform on the web. Here's what I've learned. 

***

I don't know have much of a background in coding, but I've been itching to learn GitHub because it embodies the features I value most about the open web.

GitHub is primarily used as a code-sharing platform for developers to collaborate on open source projects. It's true that most of the projects hosted on GitHub in repositories are made up of code, and most of the workflows are optimized for programming. However, GitHub is well equipped to deal with text files and Markdown, a flexible file format that is quickly becoming the standard for portable web writing. As an open and collaborative platform that deals with text files, GitHub provides an ideal system for authors (and educators) to share, collaborate, and maintain their content in the open. I first started thinking about the possibilities of GitHub for educators from [Paul Hibbitts](http://hibbittsdesign.org/), but I also tip my hat to the team at MacStories for sharing their workflow for collaborative content. Federico Viticci is always looking for ways to optimize his workflow, and as a heavy iPad user myself, I am indebted to [his guide for using GitHub and iOS apps](https://www.macstories.net/stories/one-year-of-ipad-pro/7/#github-and-markdown-editing) in this way:

> GitHub is mostly known as a code hosting platform that enables programmers to collaborate on code and keep track of changes in shared projects called repositories. At a fundamental level, however, GitHub deals with text and compares differences between versions of the same text file. The same principles that allow programmers to host their code on GitHub can be used for collaborative Markdown writing, which is what we've done through several GitHub repositories.

Collaboration is one benefit, but there are several ways to write collaboratively nowadays, whether it's Google's [Documents](http://docs.google.com/) or Microsoft and Dropbox's Word Online. "Working in the open," however, introduces a new set of challenges. These are easily solved through Grav and GitHub -- Paul Hibbitts' workflow for using the two in conjuction for an online course hub, open educational resources, and blogging takes "working in the open" to the next level.

Paul led a BCcampus EdTech workshop called ["Using the Grav CMS as a Personal Open Platform in Education,"](https://edtech.bccampus.ca/2017/01/05/grav-cms-edtech-demo/) so I followed the tutorial to setup a basic Grav site that supports [syncing to a GitHub repository](https://github.com/trent-gill/grav-skeleton-oer-content-space-site). Setting it up was easy, and I've also been updating the GitHub repository through [Working Copy](https://workingcopyapp.com/) and [1Writer](http://1writerapp.com/) on the iPad. Working Copy is a powerful Git client for iOS with a user-friendly interface, while 1Writer is a beautifully simple plain text editor for iOS. These excellent apps can be used to seamlessly write and publish content to both your GitHub repository and the website it's synced with. Combined with Paul's Grav course hub, the tips I've learned from MacStories helped create an effective way of managing a website on iOS. 

Writing and publishing to a website on the iPad can be a pain. Besides WordPress, there are very few applications for blogging on the iPad, and most of them are only compatible with WordPress, Blogger, and Medium. Although Medium undermines the open web, I can see why bloggers are seduced by its user interface. It makes writing and publishing a breeze. My goal is to create a similar workflow for any personal website, which led me to use 1Writer on the iPad combined with Federico Viticci's [Workflow for publishing to WordPress](https://www.macstories.net/ios/publishing-articles-to-wordpress-with-workflow-on-ios/). It's an elegant solution, I admit, but user automation can be tricky to figure out unless you have a lot of patience, and your CMS choice is restricted to WordPress if you're going to go this way. 

Using Working Copy in combination with Git Sync and Grav solves that problem. I don't require any automated Workflows to make these apps and platforms work together; it just works. I can work on my content from a desktop, web browser, or iPad, and it's continuously in sync without any unnecessary demands on me as a user. The benefit of working with Markdown and text files allows me to edit content and preview it in any editor I want. I'm not tied to a single document editor, I'm not creating misaligned duplicates, and I'm not required to do *any* copying and pasting. Above all, I don't have to mess around with the CMS in an iOS browser, which inevitably causes a lot of unnecessary frustration. 

My [personal blog](http://blog.trentgill.ca/) currently runs on [Ghost](http://ghost.org). I chose Ghost after deciding that WordPress was too bloated for my purposes and Grav a little too complex for my needs. Ghost has kept things simple for me; however, I haven't found a good solution for publishing to my site from iOS, and since most of my writing happens on the iPad, it creates some of the problems I outlined above. I wish that I could use Working Copy in conjunction with Ghost and Git Sync like I've setup for the local Grav site I'm testing. It's easy enough for me to copy and paste text formatted in Markdown to Ghost's editor, but what if I want to update the content after it's already published? Then, I have two versions that are out of sync: one in Ghost, and one in the text editor I used to write the post in. It's one of those technical problems that doesn't seem like a big deal until you have to develop inefficient workarounds instead of actually writing. 

## Workflow Summary

With my iPad setup, I have the following workflows:

* Write and preview full posts in 1Writer, whose document picker works seamlessly with Working Copy. 
* Make quick updates to drafts or published posts using Working Copy's in-app text editor, which supports Markdown. 
* Commit and push new posts to my website's GitHub repository with just a few taps in Working Copy. 
* Let the Git Sync plugin work its magic to update my Grav site to reflect changes to my GitHub repository. 

My Grav install is currently running on a local machine, but this is by far the best workflow I've used for the specific scenarios I've outlined. If you're an expert in customized applets in the Workflow app, you may not have the same problems. And hey, maybe it's easier to just setup a Medium account and let the platform take care of these things for you. 

The satisfaction I get from solving these problems on my own, however, makes all the trouble worthwhile. If you have any suggestions for using iOS more effectively, let me know [on Twitter](http://Twitter.com/trent_g). 

## GitHub Links

This article was originally written and published in the ways I describe in this article. I copied it to my personal blog for posterity, but in an open platform built with Grav, these two options appear on every page:

* [View This Article in Markdown](https://raw.githubusercontent.com/trent-gill/grav-skeleton-oer-content-space-site/master/pages/02.blog/grav-git-ipad-workflow/blog_item.md)
* [Clone or Contribute to This Article](https://github.com/trent-gill/grav-skeleton-oer-content-space-site/blob/master/pages/02.blog/grav-git-ipad-workflow/blog_item.md)

