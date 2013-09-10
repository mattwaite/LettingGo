#Killing Your Darlings: Matt Waite on what to do when things don't work out like you planned

Quoting developer-preacher and LA Times newsapp developer Ben Welsh, "there is nothing geeks love more than starting a project."

But what about letting one die?

Newsroom projects, like all our loved ones, are hard to let go. Every one of them starts with great enthusiasm. You have a great idea. You've got a team together. You've got a vision and some goals. Let's do this thing!

Fast forward. It launches and people love it. Users use it in ways you never thought, the story has an impact, things are working great. Compliments flow. This is awesome, right? Everyone loves this part.

Usage curves on most news projects go like this. Zero to launch to most-trafficked page on the site to the long … steady … slide … to background noise.

A month later, most likely the traffic you've got is from random Google searches. It's good to have -- you want to be someone's answer to a question -- but you've moved on. The people updating the site have moved on too. And, with that, so has the audience. 

But there's your project, still online. Still consuming resources long after the news cycle and newsroom attention span moved on. Still costing money. Maybe still costing maintenance time. And for what? Random Google noise? 

The business answer here is turn it off. Shut it down. Back up the truck. Stop wasting money on it.

But news people know there's value in longevity. A good project becomes a resource, or a momument to a moment in our history. But you can't be the first draft of history if you delete the draft. 

So what do you do?

###Have a plan

When we built [PolitiFact](http://www.politifact.com) in 2007 the only real plan we had was how we would turn it off. 

We honestly had no idea what to do if the political fact-checking website/experiment in structured data actually worked.

Our plan, if you could call it that, was that if the Florida primaries came and went and the site wasn't getting any traffic, or it was just too hard and no one was having any fun, we'd shut it down, forget all about it and go back to what we were doing before. Never happend. No one saw anything.

[It worked out pretty well](http://www.pulitzer.org/citation/2009-National-Reporting), so we never had to put the "plan" into place, but over the years I've thought about that. We should have had a better one.

I'm not about to tell you how to run your show, but I think any plan -- lets call it a Project Life Plan -- should have basic thresholds for what to do. Basically, what level of use is the cutoff where you have to do something? At what point do you say "not worth it" anymore? Depends on the project, really. 

And, really, it depends on how you build it in the first place.

###Engineer for the end

There are scores of Sharks vs. Jets dance-fights at nerd conferences. One of them is static vs. dynamic. Do you build your site out of flat HTML pages that can run on any webserver for next to nothing or do you get some servers and generate pages on the fly? 

Like any good slap fight, no one side is going to win (and the longer you fight, the dumber you look). The truth is, each project is different and has it's own set of needs. 

For instance: PolitiFact, with staffers from more than a dozen different news organizations adding content at any given time, shouldn't be built as a static site. Things are changing constantly. It's dynamic in more than the web engineering sense.

The static site argument goes like this: Servers are for chumps. You can write software to generate all those pages once, serve them up cheap and forget having to worry about server maintenance and cost.

I wish I had thought through that argument some more when I built another site in my past. It was called Edmoney.org. Don't bother going there, it's dead. I killed it. Recently.

Edmoney started out like any other project. We -- [HotType Consulting](http://www.hottypeconsulting.com) and the [Education Writers Association](http://www.ewa.org) funded by a grant from the Bill and Melinda Gates Foundation -- were excited. We had a plan, we were going to be blogging, aggregating links and -- the topper -- giving people access to data from the American Recovery and Reinvestment Act of 2009 connected to local school districts. It was going to be a deep dive into how stimulus dollars were being distributed to the nation's schools. 

And, for a while, that's what we did. The site was massive, with tens of thousands of school districts connected to hundreds of thousands of stimulus records. Staffers blogged about education dollars, reporters doing stories about stimulus spending in education submitted links for aggregation and the data got updated every quarter when the stimulus records did. 

But I should have seen it coming.

It was a grant project. And grants run out. So all that dynamic -- meaning the people and the need for all that infrastructure -- was going to go away.

Here's what I did: Nothing. There wasn't any money for a rebuild. The original scope never accounted for the end.

So I let it sit on HotType servers and chew up $90 a month. For more than a year. Because I couldn't bring myself to just kill it, even as it drew very little traffic.

What should I have done? 

Built in a switch. A switch that would have taken it from the dynamic site it was to a static site, built for archiving. It would have cost me some time on the front end and saved me money on the back. And it would still be online today. 

I should have built it knowing that someday the excitement was going to end. That the people keeping it going weren't going to be there. The data and the stories were still valuable. They just weren't worth running servers to keep online. 

The moral of the story? In all your excitement starting a new project, spend a little time thinking about the end. 

###Stick to the plan
Call this eight advanced directives for your projects, the same kind old people give their kids for when they hear that train a comin'.

1. Please, do not do what I did.

2. Do not spend money you shouldn't.

3. Do not spend time to get a site back up that no one is looking at. 

4. Do not agonize over what to do about it.

5. From the beginning, know it's not going to last.

6. Build into the project a means to mothball it, to put it into an archived state at minimal cost. 

7. Know what your thresholds are for putting it into that state.

8. And do it.

Not every project succeeds wildly. Not every project is worth active maintenance. Sometimes sites drop off the interent because they need to die.

Don't let it be yours.