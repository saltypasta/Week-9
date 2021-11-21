---
tutorial:9
date: 2021-11-21
tags: tag1, tag2, etc
---

# what I was trying to do

_play with the data from Ewan Campbell’s 2007 deposit “Imported Material in Atlantic Britain and Ireland c.AD400-800 using "R"_

+ link to the relevant github repo: like this: `[Week 9](https://github.com/saltypasta/Week-9)`

## how it might connect to other research I'm doing

_This module is about communication, so _

## what I did

+ Ran lines of script one at a time to explore the data
	+ No issues so far
+ Ran into issue, got this error code:
	+ Error in barplot(whithornCounts, main = "Forms", xlab = "Form", las = 2,  : 
  object 'whithornCounts' not found
  + Tried re running it line by line and it worked. I think I tried to run this whole bloch as one piece:
	  + whithornCounts <- table(Whithorn$Form)
		whithornCounts <- sort(whithornCounts, decreasing=TRUE)
		barplot(whithornCounts, main="Forms", xlab="Form", las=2, cex.names=.5)
+ Did the crosstab portion and got this [graph](obsidian://open?vault=obsidian-digiarch-lab-notebook-main&file=Week%209%2FCrosstab%20Barplot.JPG)
	+ Not totally sure how to read this... what do the groups mean? what are the lines within the bars? 
	+ Reading the console I can see which forms are part of each group, but group does not appear to be defined. 
	+ Asked discord for help: https://discordapp.com/channels/739577555325157407/869970599613718529/912043933532586034


_drop images, screenshots as relevant into the vault, link to them here. Use backticks to copy in relevant code snippets etc_

```
# example R code
data <- read.csv("data")
```

## challenges 

_Got this error code:
Error in barplot(whithornCounts, main = "Forms", xlab = "Form", las = 2,  : 
  object 'whithornCounts' not found_
  
 _Had trouble understanding the x-axis of the final bar plot, asked discord for help_


## thoughts on where to go next

_Asked discord, can experiment with different data in the future. Something to try for my #consolidation Doc._


