# Code Challenge - Week 5 (Mongo Databases and Full Stack Logic - Debug)

## Overview

This Code Challenge is different from the rest. This time, you will need to debug an existing code base. You will need your
complete knowledge of the past 4 weeks to successfully navigate the problems that are in the code.

Keep in mind, often debugging is stressful for a couple reasons:

* The problems are not obvious, especially when you did not write the code.

* The solutions are often simple. Have confidence in your solutions and move onto the next problem.

* Debugging code bases that are not yours takes time. Take your time to work through each of the steps.


In addition to making the changes to the code base to correct the code, update this README.md file to explain your solutions.
Meaning, in your own words, explain the problem and why your solution fixes the problem.


## TODO

### Base Mode
[x] - Mongo does not seem to be connecting correctly.
**changed the port to 27017 - added a 7**

[x] - The models have a conflict.
**i think i moved body parser when i opened app.js**

[x] - Index.html is not being properly served.
**app.get("/", function(req,res){
  res.sendFile(path.resolve("./server/public/views/index.html"));
});**


[x] - Posting information does not seem to come up correctly on the req.body as intended.
**i didn't run into this. perhaps i fixed it troubleshooting something else . running grunt to copy client files?**

[x] - The information from the database is not being appended to the DOM.
**this is updating fine. again i must have switched something updating something else**


### Hard Mode
[x] - All the information being appended on the DOM is not lining up together in their respective row.
**looks fine, announcement declared this fixed**


### Pro Mode
[x] - Not that you need to, but if you were to post this on Heroku, it would not work correctly.
**capitalize PORT**
**we'd also need to source a hosted database in the mongo module rather than a local connection**
