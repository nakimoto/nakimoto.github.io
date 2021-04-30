---
layout: essay
type: essay
title: Blueprint of Life
date: 2021-4-29
labels:
  - Software Engineering
  - Design Patterns
  - JavaScript
  - Problem Solving
---

<div style="text-align:center"><img src="https://hips.hearstapps.com/amv-prod-gp.s3.amazonaws.com/gearpatrol/wp-content/uploads/2019/09/1990-Lexus-LS400-gear-patrol-lead-featured.jpg" /></div>
 
 <p align="center">
 *Image sourced from Gear Patrol*
</p>


# Teaching a New Dog Old Tricks
 Do you ever find yourself listening to a friend's problems, only to realise that you've worn their shoes before? You start to give them advice on what you did to 
 to handle the situation. Maybe you even write down some of your most promised solutions for them to use whenever they need. Your friend shares your great ideas   with another friend, who shares it with another friend, and so on. Soon, your solutions become a blueprint for similar problem solving between a group of mutual friends.
 
I recently came into the possession of a 1990 first generation Lexus LS400. This car is 31 years old but only has 18,000 miles on it. It has some wear and tear to the paint and to the trimming on the back. There was also a part on the bumper that needed to be filled with automotive body filler. At AutoZone, there are these little tools you can buy that were originally designed for spreading body filler over a surface. This is their intended purpose, so I purchased them as a solution for my initial problem. 

After doing the body filler, I moved on to begin replacing the trimming. I realised I had a new problem! I didn't have the specific tools to remove the old trimming from the car. When looking around on Amazon for the tools, I noticed that they have similar designs and elements of the body filler tool. They are both scraper like tools made of plastic that are used in order to not scratch automotive body paint. I got to thinking...what if I applied my previous solution from before...for my new problem? Naturally, I tried it out. I sat my car in the sun at the local park and waited a while. I took my plastic scraper and started slowly removing the trimming and it worked! There wasn't any need for me to come up with (or purchase) a new solution, because I could apply a similar solution from before. 

I ran into this situation again, when I accidentally oversprayed repair paint onto my back window. I now had another problem. Like everyone these days, I went directly to google and youtube for a solution. I watched a video where an individual used a sharp razor blade in a downward motion in order to scrape the overspray off. However, I have tinted windows. My back window especially, has some bubbling of the old tint and i didn't want to cause harm to the tint overlay. I applied my same thinking from before. "How did I solve my previous problem?". When examining the razor blade, I realised the solution existed in the concept that it was applied at an angle, and it was sharp. I knew another tool that was sharp and angled...my scraper! The same one from before. The idea, or blueprint of the solution was the same. Application was different.

## **I was teaching a new dog old tricks.**


# Oh, how nice it would be! to have a (software) Blueprint of Life. 

<div style="text-align:center"><img src="https://i.pinimg.com/originals/6c/90/28/6c90288d7e10d46d18895f17f420a92c.gif" /></div>

 <p align="center">
 *Image sourced from pinterest*
</p>


I have been working with three other people to create an application for a student budget-friendly meal website. Ideally, my group and I would like to have a functional web application that can be used to create, share, and favorite inexpensive recipes that can easily be made by the average college student. I have been implementing testing for the application's functions using testcafe. The test controller moves through the different pages and functionalities we currently have. 
While writing up the tests, I realised that any of the problems I ran into with matching IDs on pages with the testcafe file itself, were just a reiteration of a problem before. I had an issue with our add recipe page not passing testing. An error message was displayed on my terminal letting me know that the "specified selector didn't exist in the DOM tree", meaning the selector IDs didn't match so the test controller couldn't access it. 
I was able to fix this renaming the selector to match the ID. Carrying on, I encountered a similar problem with an administrator page. I realised that this was a similar issue, so theoretically, I should be able to use a similar solution or idea. 

This time around, it took some extra elbow grease. Instead of simply matching IDs, I went back into commit history to see all the individual changes to our main GitHub repository branch. I saw that there was a commit in which someone changes IDs when creating a page, but it wasn't necessary. I had to go back and change all of the IDs to the previous form, and apply my solution(s). I also realised the test controller had to be logged in with administrator credentials, and not user credentials. I went back to look at my solution for adding recipes (and other pages) for how the test controller logged into the user. I applied that same idea and had the test controller log into the administrator to complete it's testing. 

 <p align="center">
 **It worked!**
</p>

*Are all of life's problems solveable by a common solution?* well...I'll let you know when I turn **100!** 



 

