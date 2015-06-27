---
layout: post
title: Week three
---

This week was a lot of fun! Our second project was much more complex than the first one. I partnered up with Nari and we were able to successfully do pair programming for most of the project. The project was called Netflix and we were supposed to create a prediction machine for predicting what a customer is going to rate a given movie. We had to brainstorm some to try to figure out what would be the best way to predict the rating. Eventually, Nari and I settled on three things for our prediction: The average of all the ratings that customer has given so far, the average of all the ratings for that particular movie, and the overall average of all the ratings for all movies from all customers.  That seemed to work out well as we were able to achieve an RMSE of 0.97 for a large text file, our goal being an RMSE less than 1.00. 

After the project was turned in, we had a very interesting class on Wednesday. Everett Toews from Rackspace was our guest speaker and he gave us a talk about the Cloud and Rackspace development. Everett went over the framework of Openstack and Rackspace, discussing all of the important functions of the two. The most important part of this lecture was him showing us how to spin up a VM on Rackspace. We will be beginning our 5 person group project next week so we need to know how to start up a server and make it secure. 

On Friday, we went over some odds and ends of Python to help us prepare for our Test on Monday (which I am absolutely nervous about). We learned about these three tokens: “*”, “**”, and “=”. All of which behave differently when used in a function call and parameter list. I am so used to Java’s strict rules about parameters so it was a little surprising that Python has this type of flexibility. It definitely provides the programmer with more freedom and control. 

Tip of the week: Do not take merges on GitHub lightly. My partner and I had some merge conflicts this week which resulted in some of the code being lost. We were able to get everything back up to date but it was still time spent that could have been spent elsewhere. Be sure you pull before trying to push and if there are merge conflicts, use GitHub Mergetool.
