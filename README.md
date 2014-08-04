#Triggers, A deep dive.
### No Experience Required.

#Introduciton
Hi. My name is Kevin. I solve hard problems. Sometimes that involves writing code, and sometimes that involves taking complex things and making them simpler. Mostly, it means listening and stripping away needless complexity around really simple things. Salesforce Triggers are often understood to be very complex, hard and intimidating things, best left to highly motivated people who have an affinity for star-wars sheets and genetic predisposition to nearsightedness. This, however, is simply not the case. Throughout the course of this tiny ebook, we're going to unwrap triggers from the myth and legend and talk about composing them step by step.

This will, of course, require some Apex code. *Wait!* don't run away. Despite the intimating wall of code you see on the monitors of developers everywhere, the fact is that Apex code is nothing more or less than the same type of logic you use everyday via the Salesforce delcarative user interface. We're going to talk about some Apex basics before we dive into how we use it for triggers; don't worry, we're taking small, reasonable steps and I promise we'll walk before running.

#Context
- What (object)
	- meeting attendees record
- When (before/after action)
- Why ( are we running a trigger ?)

#Logic, we haz it.
- Work in bulk
- Use trigger.new / trigger.old or trigger.oldmap / trigger.newmap
-
