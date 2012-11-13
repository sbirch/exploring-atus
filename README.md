exploring-atus
==============

Adventures of Sam and Jonah in the Bureau of Labor Statistics

All data is from the 2011 ATUS.

*Files in this repository:*
 * activities.jsonp - JSONP bound to _DATA() with every case and every one of their activities
 * activities_every_15m.jsonp - a subsample of cases linearized into 96 points in the day (every 15m)
 * lexicon-2011.json - the 2011 activity code lexicon
 * popular-codes.txt - popular codes for random times in random cases in the linearized activities (None means no activity recorded)

*TODO:*
 * Switch to a nicer library for representing the timelines (something element based)
 * Think of a way to summarize / compress the hordes of people
 * Try parallel coordinates?
