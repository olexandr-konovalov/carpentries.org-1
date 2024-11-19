---
layout: page
authors: ["François Michonneau"]
teaser: "New survey systems for our workshops"
title: "A Better Experience for Workshop Surveys"
date: 2019-10-21
time: "09:00:00"
tags: ["Assessment", "Carpentries Workshops"]
---

Assessment is a key element of our operations. Today, we are excited to announce that we are revamping the tools behind our pre- and post-workshop surveys to provide a better experience to our learners and to our instructors. This change also greatly reduces the time needed for the workshop administration team to generate the links they share with instructors to access the results. The changes outlined here only affect our regular workshops, but in early 2020, they will also affect Instructor Training events.

## What's Changing

### 1. Everyone answers the same questions

For about a year, Software Carpentry, Data Carpentry and Library Carpentry workshops were using a very similar (if not identical) surveys for their workshops, but there were three different links to access them (one for each lesson program). Starting today, the three lesson programs will use the same link for their respective pre- and post-workshop survey.

### 2. A better experience for learners

We are switching from SurveyMonkey to Typeform to collect the answers to the pre- and post-workshop surveys. Typeform provides an intuitive interface that works well both on desktop and mobile devices.  Answering the surveys is faster which we hope will increase the proportion of participants who take them.

### 3. A better experience for Instructors

Shortly before a workshop, the Instructors and the hosts receive an email from one of our workshop coordinators that contains two links to access the results of the pre- and the post-workshop surveys. There will now be a single link that will give Instructors access to both the pre- and the post-workshop survey results.

Before, the presentation of the survey results wasn't optimized for the specific needs of our workshops. It was generated by the standard template provided by SurveyMonkey. Additionally, answers to each question were shown in two different formats, and some answers were not useful. This led to a lot of scrolling which diluted the message conveyed by the results of the surveys. Now, we present graphs only directly relevant to the Instructors in a more compact form that allows Instructors to get to know their audience better, and highlights how the workshop went more clearly.

## How Does It Look?

Below are some screenshots (based on fake data) that show what instructors will be able to see:

![screenshot showing frequency distribution of operating systems](/blog/2019/10/typeform-transition-os.png)

![screenshot showing the frequency of use of different tools](/blog/2019/10/typeform-transition-frequency-use.png)

![screenshot showing the change in confidence/skill scores](/blog/2019/10/typeform-transition-change.png)

## Did You Test It?

We tested an early version of this new workshop survey experience in early 2019 on 12 workshops and collected about 300 responses for the pre-workshop survey and 120 for the post-workshop survey. Instructors who used this system rated it 4 out of 5 (and it was an early prototype with some bugs). Instructors familiar with the old system (using SurveyMonkey) commented that the visualisations were clearer and enjoyed being able to get the results for both surveys in the same place.

## When Can I Use It?

The [pull request](https://github.com/carpentries/workshop-template/pull/628) to update the link on the workshop website template has just been merged. This means that any new workshop website created from now on will use the new survey system, and the workshop administrator will send you a link to access the results.

## What's Next?

One of the most exciting features of this new approach is that we can control the code that generates the visualisations that are presented. We are hoping that Instructors will give us feedback on how we can improve how the results of these surveys are presented and analysed so they can prepare better and improve on their teaching.

We'll soon pilot and use this new system for our Instructor Training workshops as well.

## How Can I Help?

We are planning on open-sourcing the code behind this before the end of the year. Before that, we'd love to have a full code review by a community member. If you are familiar with [Shiny](http://shiny.rstudio.com/) and are interested in reviewing the code before it's released, please get in touch with François ([francois@carpentries.org](mailto:francois@carpentries.org)).

## Acknowledgments 

The presentation of the survey results was developed using feedback and ideas from members of The Carpentries community including Ben Marwick, Katrin Leinweber, and Katrin Tirok.

For any other questions about this new system, please reach out to [team@carpentries.org](mailto:team@carpentries.org).