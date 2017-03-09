---
layout: essay
type: essay
title: "Meteor Gotchas"
date: 2017-03-09
labels:
  - Software Engineering
  - Meteor
---
<img class="ui tiny right spaced image" src="../images/meteor.png">*Problems in meteor*

# Solved Problem

A problem that I had initially encountered that I was later able to solve was during a timed WOD. This issue occured during an unfortunate
time since it can be difficult to solve issues under timed conditions and I was also very new to meteor making it that much more diffcult.
The WOD involved providing a helper function that would print "That's a lot!" when the counter reached greater than 5 in the localhost
homepage. I had thought I successfully implemented the helper function into the javascript file but everytime I went back to localhost to
check if anything printed, nothing would show up. It was only until later that I realized that I needed to call upon the helper function
in the html file using {{function}}. It was not obvious at the time because I thought that only modifying the javascript was necessary and
did not think of the html file which is what controls what appears on the website. Now I know that it is important to consider all files
and to think through the functionality of all of them before giving up

# Unsolved Problem

One of the problems that I had encountered was during the leaderboard excercise. I was changing the leaderboard.html and when I went to check
the localhost:3000 it had crashed. I went to check on the command prompt and it had said the server had crashed due to a duplicate 
<head>. It stated that <head> was already provided and that I needed to delete the one in my source code. But, even after deleting it 
nothing had changed the server just kept trying to refresh but the localhost server was never put back up. One attempt at solving this
was that I first stop the server and then deleted the entire html file. Then, I replaced the html file with a new one hoping that the last one
was just buggy and this new one would solve the issue. I tried to then put the server back on but it was unable to be run. I am still not
sure what the issue was but after the leaderboard excercise I never encountered that issue again. 
