# Welfare Traps in Practice - A New Zealand Perspective
### Harry Elworthy - harryelworthy@gmail.com

Over the northern hemisphere summer of 2017, I worked at the New Zealand Labour Party as their only leadership office intern, doing economic analysis. This was election year, and given that Labour was not in office, things were hectic and understaffed. Economic work was done by the Finance Minister, the Senior Economist and me, an undergraduate. It was a fantastic experience, and an extra satisfying one when Labour eventually won the election and put into power the world's youngest female head of government, and the only head of government in modern history to have a child on the job.

Before I arrived, I put together some graphs on the (then) current welfare system in New Zealand. These graphs didn't get used very much, but I think they tell an interesting story, and so thought I would put together a quick write up about what they mean and why they show problems that are important to any country. They were created in [this messy Jupyter Notebook](WorkingForFamilies.ipynb), so you can follow along and play with the data there if you want.

This is the most important graph:

![Figure 1](https://github.com/harryelworthy/Labour-Welfare-Work/blob/master/Take%20Home%20Income%2C%20Single%20Parent%20Working%20for%20Median%20Income.png)

This graph shows take-home income on the Y axis and hours worked on the X axis, both weekly, for a single parent at the median hourly wage, not seeking Jobseeker or an Accomodation Supplement, and not in NZ as of 2017. In a world with no taxes and benefits, this would be a straight line from the origin, with each hour you work getting you the same amount of income.

The obvious jump scare is the kink at 20 hours. This kink is the result of the In Work Tax Credit, henceforth the IWTC. The IWTC works by guaranteeing any worker with children that works over 20 hours per week (or 30 hours for a couple) a given amount of take home income by providing a tax credit, and then phasing that credit out as income rises. The motivation here is clear - to provide welfare to the poor that also creates an incentive to work. Looking at the graph, though, it's clear that there are two incentives at play: The incentive to work marginally more for those working less than 20 hours a week, and the incentive to work marginally less for those working more than 20 hours a week. This is because for the almost 10 hours of work above 20 hours, this person takes home no extra cash. They are guaranteed a certain income, so they can earn more beneath this guarantee and take nothing extra home. 

This is clearly a problematic policy! No government should aim to hold their workers, especially those with low incomes, at 20 hours a week of work. Not only this, but there can clearly be issues here for people with variable weekly hours. Suppose your boss gives you 21 hours of work one week, and 19 the next week - that's a difference at home of close to 200 dollars, about a third of your weekly income! That's a huge money shock, especially to a single parent. And yet the IWTC has been in place for many years under opposing governments, with no visible plans from either to dissolve it. 

Besides the large kink, there is something else to look at in the graph: the flattening gradient of take-home income as hours-worked increases past 30. This is the phasing-out-with-income of the IWTC, as well as two other similar policies, mentioned above. Although less striking to the eye, these phase-outs have a similar effect to the above: they discourage work. Although this person is only paying a ~10 percent tax rate, they are starting to see effective marginal rates higher than that - often over 50% - meaning that half their extra marginal income is eaten away by abating benefits. They work an extra hour, and they get a bit less of benefit A, a bit less of benefit B, and pay tax, and suddenly they haven't earnt so much extra.

The interesting thing with these phaseouts is how they stack up over different benefits. See below, where I include the same graph, except with an extra line, this time for a person who *is* seeking an accomodation supplement. This benefit abates similarly to the others, falling off with income.

![Figure 2](https://github.com/harryelworthy/Labour-Welfare-Work/blob/master/Take%20Home%20Income%2C%20Single%20Parent%20Working%20for%20Median%20Income%2C%20with%20Accom%20Supplement.png)

The accomodation supplement is, by and large, a well designed welfare policy. It gives almost all low-income citizens a lump sum payment that corresponds to the cost of living in their area, and this lump sum phases out to a fairly high income level at a low rate, meaning that there isn't a sharp kink as above, and many people get some of this supplement. It's simple and effective: give money to the poor. One could argue that the government should not be subsidising people for their choice to live in expensive areas, but even that may not be true with the benefits of density. Given all the terrible welfare policies in place around the world, this seems pretty fine.

The problem though, again, is the phase out, which is 25% per dollar earned. A policy like this needs to be phased out - the government cannot afford to give this lump sum to everyone. But when that 25% phase out - what is effectively a tax on income - is placed on top of other phase outs and actual income tax, you get a very flat earnings curve, as we see above. The accomodation supplement makes this person better off at every income level than before, but it also further disincentivises them from working more.

This is the definition of a welfare trap: someone is poor, and the government helps them, but in doing so the government provides bad incentives for them to reach higher income levels. If you were this person, and you had your take home income vs. hours worked graph up on your wall (as you should), how many hours would you be working? 20 hours a week looks mighty tempting...

Much more importantly, how much effort would you put into finding a higher paying job? Say you found one that paid you 5 dollars more per hour, but that meant all your benefits were dropped significantly, and you only ended up taking home 2 dollars per hour. Would you pursue that job with as much energy as you otherwise might have?

This more long term view of welfare traps, as something that tempers the ambition and forward planning of people, is the one that shows true harm. Welfare should provide for those in poverty, but not at the cost of denting their reasons to try and make it out of poverty.

These traps happen in every country. They are hard to avoid, and in some cases cannot be avoided entirely. But they should be noticed. Abatement rates should be kept down. Benefits should not be thrown on top of one another, especially when all abating in tandem. Kinks should be smoothed. These are boring minutae of benefit policy, but to those people facing a tradeoff such as faced by our unnamed single parent, these minutae can have huge effects.



Other topics that I could touch on:
* How labour monopsony/frictions mean that very few workers actually choose their hours, and how that makes the income variability of kinks worse
* How the policies are designed to be opaque, how this makes the policies work better but also rougher on low income people. No calculator, very tough to work out exactly how much benefit a given person will get, going through multiple agencies etc. The idea is that for a real person doing it, they go to WINZ and get told how much they will get. There is something sour about policy designed to be opaque 'for the good of the people'
* The tradeoff a government makes when costing these policies between giving a shallow (and forgiving) phase-out steepness and making a cheap policy. Rich people on benefits are expensive! 