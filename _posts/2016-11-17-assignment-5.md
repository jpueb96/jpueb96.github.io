---
layout: post
title:  Assignment 5
date:   2016-11-17 
author: "Jailine"
categories: INLS161
---

Assignment 5 was a continuation of assignment 4, but more complex.  We used MySQL to create a database to display the results obtained from the original script.
Dylan has more advanced skills so he was able to input the arguements into the script to ensure that it ran properly. The script basically asks the questions we came up with, there is time stamp to show when the response was recorded, it also asks for your username, and it automatically dumps the latest version of the results into the database so it does not need to be dumped every time the script is ran. 
Emma and I worked together on tasks since we are still developing our skills.  We collaberated on created the database; we got stuck when creating the database because we tried to copy and paste the example into the command line to save time, but we discovered that you are unable to edit the text when that is done.  After we created the database, Emma created a dump since the database was created on her account.  Dylan and I then had to import the database from the dump; we worked in sync when pushing, pulling, and dumping. Although the script ran fine, we ran into some minor trouble that made the script not user friendly.  One problem was that the script asked for a password after being completed, although the passwork was simply blank, it was not ideal to have.  Dylan figured out the `-p` had to be removed from the command, solving the issue.  Another issue that we ran into was that when an apostrophe was used an answer on the script it would interrupt it and we would recieve and error.  Emma and I worked on solving this issue, we resorted to Google to try to figure out what could be done.  We eventually found a random string that allowed apostrophes to be inserted without interrupting.

[Assignment 5 Repo](https://github.com/emmacai/groupsed)