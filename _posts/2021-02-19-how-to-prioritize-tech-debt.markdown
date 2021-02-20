---
layout: post
title: How to Prioritize Tech Debt
date: 2021-02-19 13:32:20 -0700
description: Align your team behind a prioritized list of tech debt.
img: i-rest.jpg # Add image post (optional)
fig-caption: # Add figcaption (optional)
tags: [Tech Debt, Software, Leadership]
---
Often teams have a lot on their mind when it comes to technical debt and it’s not always clear how to best address it. I have a process I like to use that includes the entire team and the outcome is a prioritized list of initiatives that the team is aligned behind. The process is called the Effort/Impact Matrix and is used quite frequently in product management. Although scientifically imprecise I like that this process aligns the team on what the next most meaningful technical debt projects are.

## Overview
* Setup
* Brainstorm
* Present
* Group
* Sort Effort
* Rank Impact

## Step 1 - Setup
Organize a meeting for the entire team including Product and Design. For in-office teams, bring sticky notes and sharpies for everyone to collaborate. Make sure that there is space to post sticky notes on a whiteboard or wall. For remote teams, Create a new [Miro board](https://miro.grsm.io/traviselnicky639) and invite your team to it. [Miro](https://miro.grsm.io/traviselnicky639) is a great tool for remote collaboration and will be perfect for this activity.

## Step 2 - Brainstorm
Take 5 mins and have each person create a list of tech debt items to consider. Make sure that each person works by themselves to create their list and that each sticky note contains one tech debt item. Having each team member work individually will ensure that you are able to collect unbiased ideas from everyone. There is no limit to how many or few stickies to create, the point is to just get as much out into notes as possible.

![List of sticky notes]({{site.baseurl}}/assets/img/tech-debt-step-2.png)

## Step 3 - Present
Once everyone is done writing their thoughts down have each person present their list to the group. As they read their sticky notes collect them on a board and begin to organize them all together. Allow for the team to ask questions about the ideas posted and if new ideas come to mind make sure to include them on the board. At the end of this step the team should have a good understanding of what everyone wrote down.

![Combined list of all sticky notes]({{site.baseurl}}/assets/img/tech-debt-step-3.png)

## Step 4 - Group
Now you have a large group of loosely organized ideas. With the team, combine duplicates and group tech debt items that would be apart of the same project. If two related tickets can be worked on and add value independently don’t group them together as one project. The smaller the deliverables the better.

![Grouped sticky notes]({{site.baseurl}}/assets/img/tech-debt-step-4.png)

## Step 5 - Sort Effort
Horizontally align each ticket or group and begin to sort from lowest effort left to right. Don’t get too hung up on the estimates, lowest effort is not a science and imprecise but with your team you should be able to get a “good enough” gut feeling. Often you can compare each project to each other and gauge whether one would be bigger than the other.

Effort is how long it will take for your team to deliver the project. If your team has been working together for awhile you should have a pretty good idea of the team’s capacity. I like to use the unit “Dev Days” when reviewing each ticket. 1 Dev Day is equal to a single engineer working for 1 business day. Hypothetically if something estimated at two dev days can be parallelized across two engineers it should only take one day to complete. Obviously not everything can be parallelized so take care in considering work that must be serial when estimating.

![Horizontally aligned sticky notes]({{site.baseurl}}/assets/img/tech-debt-step-5.png)

## Step 6 - Rank Impact
Go through each project and rank by Impact, the more impactful a project is the higher on the board it’ll be. Some tickets will rise above the horizontal line you created and others will fall below. Again this is not a perfect science but you should be able to get a good directional idea from the team.

Impact is the value you will deliver to the customer. In terms of technical debt that may mean your team is able to deliver faster, handle more traffic, or deliver faster page loads. A unit you could use for this is total number of users impacted, however this is just an estimation exercise so don’t get hung up on assigning specific values to projects.

![Vertically ranked sticky notes]({{site.baseurl}}/assets/img/tech-debt-step-6.png)

## Conclusion

![Sticky notes with high effort and high impact axis]({{site.baseurl}}/assets/img/tech-debt-conclusion.png)

The final list that you end up with is a matrix of projects, anything that is low effort and high impact should stand out as something to do asap. With the team talk through the results and determine what you’d like to work on first. It won’t always be the case you just take the most impactful and lowest effort but now you have a shared visual of how the team is thinking about their tech debt to consider.
