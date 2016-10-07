# long_haul
Periodic notes about my progress.

## 10/6/2016
### Goals
Overall: 
Code and do a little planning.

Objectives: 

1. Try cloned flask blog locally, modify as needed (or use to troubleshoot your own), and add to website.

2. Review task planner for new meetup friend.
 * 

3. Review possible outreachy projects with an eye for Python, projects with tags for beginners, and helpful documentation.
 * 

4. Intro to D3 with RC folk
 * Recent version v4 came in June, naming is different so old tutorials need to be translated
 * More tutorials for v3 but v4 is more recent
 * Docs on 3D.org site are current
 * can't just copy/paste your data in and see it
 * 3d good at mapping length/height/etc to your data attributes, but making those relationships is hard to get your head around
 * easier to learn with JS knowledge
 * ES6, etc. means that it is a version of JS
 * mapping data onto html element or svg (Scalable Vector Graphics - eg. squares etc) element
 * divide 
 * tributary.io helps you see what selectors
 * really helpful to use inspect elements when using D3, D3 will create your elements for you so you can check for them inside your inspect element to troubleshoot when you don't see what you expect
 * maybe it is easier to learn without chaining at first (append as a second step) but all the examples have a lot of chains
 * make sure to name your collections of items and then you will change your attributes (circles will stay circles even if they multiply, turn red, etc.)
 * select and select all are the two ways to select, select all will not select things but it will make a place to collect those things, which is weird to think about
 * make a cheat sheet of commands to make collections that don't exist - very smart

5. Dynamic programming talk by **, slides **
 * Hard to know what is a dynamic programming problems
 * Foscus this time on getting formulation right, coding comes easier
 * Problems selected are famous
 * Richard Bellman, father of dynamic programming needed a good name that didn't sound like research 
 * Bellman-Ford algorium
 * Motivation: recursive formulation is in definition of the problem but niave solution is going to take a very long time
 * Sometimes get a list of integers and need to find the ones with some property and in that case there is no notion of sequentialness
 * Not just considering location but also which house is bigger (and you can steal more money from)
 * Use answer from subproblem (2) and have that be your starting house
 * Memoization keep answers off to the side in a dictionary and check if you solved the problem before
 * Python3 has a memoized decorator 0_o 


## 9/16/2016
### Goals
Overall: 

Code. Hopefully mostly Django.

Objectives:

1. [Learn to be a master-googler](http://www.powersearchingwithgoogle.com/) [Unit 2]
 * Context helps when search results give more than ask for 
 * Knowledge panel is basic information about the thing (all clickable items), useful in supporting your search
 * Autocomplete is driven by what others have searched (in the dropdown)
 * Google instant fills in results for the search you are starting (in the browser page) - you may be able to reconize the thing you are looking for
 * Searches related to might get you thinking outside your box (ie. family name but doesn't include the name itself
 * Read more carefully: don't skip words you don't know (define: <word>)
 * Grey arrow widget gives more information about word (timeline of use, etc.)
 * Can use words not in dictonaries because defined by content on the web
 * Lots of content on google, blended into search results webpage
 * Look beyond the webpage for insights: related searches (at bottom), different media types
 * Different media types: images (along top), news
 * If first results are videos, check out the video tab and choose what looks best
 * Reading Search Engine Results Page
 * If new to a subject break down question into single questions (ie. if unsure of definition)
 * Open links in different tabs (cmd+click)
 * Words in query and snippet will be bold in the snippet
 * Downward arrow will tell about the website/org etc. - way to get quick sense of how authitative that sourse is
 * ... means something has been removed and maybe information that would be helpful to you has been deleted
 * Links at bottom are places within that webpage that people go to (results from within the site)
 * If results seem to contriduct each other mean you need to investigate further 
 * Tools to look for patents, scholar, etc. to search for those types of content
 * More dropdown offers Google books, etc.
 * Can search for google books etc so not have to remember the URL
 * Patents searches use advanced tab
 * Legal content only in English so switch to English as your input language
 
2. [Learn to be a master-googler](http://www.powersearchingwithgoogle.com/) [Unit 3]
 * Google can crawl visible web, non-indexed is deep web
 * Operator filters your results (ie. "tesla coil site:standford.edu"), when you need a particular thing from a particular place
 * site: operator used as domain (.edu) and website levels
 * filetype: operator limits results
 * Can import kml file to maps (neat sidebar)
 * Format [query terms filetype:<type>]
 * - operator filters to exclude certain results
 * Format [query -<irrelevent sense of the word> -<ingrediant you don't like>]
 * No space after minus sign or will emphasize that word
 * When exact phrase "<phrase>"
 * "<blah blah "blah">" good way to avoid similar spellings, means third blah will not be spell corrected
 * OR adds more results to your search, Ex. Fish spa OR pedicure, bolded term in summary is the term that was used
 * intext: operator makes sure text is on the page
 * Important because not all terms are always included, sometimes page ranks highly enough based on first terms that you get that page without considering later terms
 * Settings to go to advanced search and will be populated with your search
 * If you forget operators, etc., come here
 
3. [Learn to be a master-googler](http://www.powersearchingwithgoogle.com/) [Unit 4]
 * Search-by-image (search internet for images) : click image search in upper right, drag image into search bar
 * Where from, what is it? Example of tool-like item on white background because assuming will be in catalog
 * search "Google Search Features" for complete list of shortcuts
 * Conversions: X units in units that interest you
 * Won't give you length into volume, instead gives pages that mention both conversions
 * Can do lovely 3D graphs of equations
 * Easter egg is asking questions and adding the answer (ex. Number of horns a unicorn has + the lonliest number)
 * Subpanel can change location, any time (time page was published to web, can have custom range using wiget to see how the world felt about a thing in a certain time range)
 * Examples of previous unit skills: California OR CA intext: other politician from that time
 * To learn what others think, search in their language using advanced search menu
 * Bar along the top will over to translate to your default language - can go back and forth
 * Text in images aren't translated
 * Can define a region in addition to a language so in Spanish served from Mexico for example
 * Better to search for the translated word instead of in English 
 * If you paste URL into google translate, will give new, translated URL

4. [Learn to be a master-googler](http://www.powersearchingwithgoogle.com/) [Unit 5]
 * 
 
 
 * 
 
 
 
2. Mediem and long-term goal thinking
 * Think about favorite companies
 * Remember not to be scared of the JS and the PHPs of the world

4. Work on Django blog
 * 
 
5. Review of Recurser's geology game
 * 


Tabled: 

1. [Khan academy has a diagnostic to find the limits of your math skill](https://www.khanacademy.org/mission/math)

2. Probability course review

3. Django website contribution

4. Review counting

Distractions:



Neat things:

1. 

Notes:

1. 



## 9/15/2016
### Goals
Overall: 

Review code today and think broadly about what you should be doing.

Objectives:

1. [Learn to be a master-googler](http://www.powersearchingwithgoogle.com/) [Unit 2]
 * 

3. Review math program
 * My copy of my review can be found [here](https://github.com/rczyrnik/MathProgram/compare/master...vzhz:codereview).
 * I struggled a little about keeping track of which branch I was on and how to push to a practular branch from my cloned repo that I had forked from her.  There is a good review of the process [here](https://help.github.com/articles/pushing-to-a-remote/).
 * This reminded me of what I am comfortable with and what I'm not, and I hope to remember that as I go forward.
 * I also asked the pairing stream at Recurse to review my review, since I want to be able to improve my clarity.
 * Next time I think I will comment in github and not inline so no one has to delete my comments in the future, but I decided that this was the way I did it and it was time to move on instead of "perfecting" something that doesn't change much for the other person even though it would take me a lot of time.

4. Work on Django blog
 * 
 
5. Lightning talk tonight about cell phone transition
 * Decided to cancel and stay home for all roommates stay home day instead.  The talk was going to be amusing but wouldn't benefit you like the work you got done.  Go you.

6. Counting review with Recurser
 * Rescheduled because of stay home decision.

7. Django website contribution
 * Asked a question about one of the issues on the depricated version of their website (oops)
 * Tried to identify a issue to tackle for the current site

Tabled: 

1. [Khan academy has a diagnostic to find the limits of your math skill](https://www.khanacademy.org/mission/math)

2. Probability course review

Distractions:

I think it would be a helpful to take notes thoughout the day as I was doing before.

Neat things:

1. 

Notes:

1. Should think about what your long term goal should be.


## 9/14/2016
### Goals
Overall: 

Not sure what my plan had been, but what I actually did was configure my new phone.

Objectives:

1. Get your phone set up.
 * 
 
Tabled: 

1. [Khan academy has a diagnostic to find the limits of your math skill](https://www.khanacademy.org/mission/math)

3. Review nweb's math program

4. Work on Django blog

5. Probablity

6. [Learn to be a master-googler](http://www.powersearchingwithgoogle.com/) [Unit 2]

Distractions:

Neat things:

1. 

Notes:

1.

## 9/13/2016
### Goals
Overall: 

Get some coding done today.  That's what you really want to do.

Objectives:

1. [Learn to be a master-googler](http://www.powersearchingwithgoogle.com/) [Unit 2]
 * 
 
2. Get math materials for probability course review
 * Old math prof suggested reviewing the combinatorics/counting sections of “A First Course in Probability” by Sheldon Ross (Ch. 1) and then attempt to read Knuth.
 * In the course, text was “A First Course in Probability” by Sheldon Ross and we covered chapters 1-5, the first half of 6, parts of 10.
 * Hard copy of the book is [on ebay](http://www.ebay.com/itm/FAST-SHIP-A-First-Course-in-Probability-9E-by-Sheldon-Ross-/262440734464?hash=item3d1aafcf00:g:6JAAAOSwXSJXOkLw) but there is also [this pdf](http://zalsiary.kau.edu.sa/Files/0009120/Files/119387_A_First_Course_in_Probability_8th_Edition.pdf).  Nothing in the NYC/Brooklyn public libraries, but now you have a library card on the way.  Pdf now downloaded onto your desktop.
 * Found a buddy to work with at RC on Thursday!
 * Try to review some on Weds so you're ready to pair.

3. Review nweb's math program
 * 

4. Work on Django blog
 * 
 
5. Thought of future talk/lightning talk ideas

Technical:

 * How the http requests library works
 * Webscraping in Python (project review + best practices/how-to)
 * Building something simple and modularly building up from that 
 * When PEP8 is and isn’t helpful (Python specific)
 * Review of “Unlocking the Clubhouse” (short talk)

Non-technical:

 * Lessons I learned helping with rover landing site selection 
 * Learning to fly and how it is like any other learning process (I need to think about how to frame this, but it could be awesome)
 * Comical talk about switching from a dumb phone to a smart one
 * Somedat I want to share my favorite life hacks

Tabled: 

1. [Khan academy has a diagnostic to find the limits of your math skill](https://www.khanacademy.org/mission/math)

Distractions:

I started getting the white lights in the corner of my eyes thing.  It was so bad that when I took a "please be better, eyes" walk and visited a shop, it was hard to talk to the saleslady because I couldn't see her very well.  Not the best thing.

Neat things:

1. Went to PythonNYC meetup for like 20 minutes and talked to a Recurser who suggested you watch [Destroy All Software's talk on Boundaries](https://www.destroyallsoftware.com/talks/boundaries) to better be able to apply the counting you will be doing with him.

Notes:

1. Spent a non-trivial amount of time figuring out travel to Boston, Airbnb stuff, etc.

2. Django project guy didn't write me back, should I just do a small PR or wait (I assume he's just busy)

3. Totally didn't try not checking my email in the morning.  Eye pain meant I let myself work on brainless stuff (Airbnb, etc) alot. :/

## 9/12/2016
### Goals
Overall: 

Finish the things you didn't finish yesterday, but somehow do this only until it becomes boring and move onto things you find wonderful.

Objectives:

1. [Khan academy has a diagnostic to find the limits of your math skill](https://www.khanacademy.org/mission/math)
 * Nope, didn't

2. [Learn to be a master-googler](http://www.powersearchingwithgoogle.com/) [Unit 1]
 * Be articulate about what you want and limit scope
 * [Google <country>] will show you that country's google
 * Filter your results with search tools (eg. by color with search tools>dropdown across the top>color)
 * Can use multiple filters at once in search tools (eg. name that is a make of car and a died inventor + tools>type>faces gets you pictures of the inventor)
 * If amiguous, add another word (eg. Tesla vs Tesla coil)
 * Think of what you need (eg. diagrams are often in black and white)
 * Actually searching google's index of the web, fetched with spiders
 * Asks questions to determine what you need: how many times do keywords occur on page, are the search terms in the URL, or directly agacent, does page have synonims for the search terms, what is quality of page, what is its page rank
 * Ads along right and top
 * Similar results and cached version of the page at the bottom of the description
 * Words in your search term don't have to be found near each other in the page
 * Ketword choice: think about what you are trying to find, chose words you think will appear on the page (what would the author say (for medical care, "broken arm" not "busted arm")) 
 * Insertion is extracted from some webpage to answer a question ("question answering"), not reliable yet
 * Take out the words that make it a question
 * Think of uncommon phrases that describe what you want (eg. ghost town)
 * Every word matters (eg. "who" vs "a who" vs "the who") and word order matters (eg. sky blue vs blue sky (names of businesses))
 * Capitalization doesn't matter
 * Doesn't reconize most special characters, but #, +, $, @, % ok if not by themselves (eg. #hashtag)
 * Awesome spell correction (or Veronica would never find anything) with assuming you want the famous thing and then offer "search instead for <your spelling>"
 * Find function ctrl+f for finding text on page, enter for next entry, different browsers put search in different locations
 * Scroll bar will be colored with lines at the point of the document that your search term appears
 * Using speeds search by 12%, 90% of people don't use it, tells if word appears or not (eg. person never ran in this race if name isn't on the page)

3. Contact Django-website-testing-folks and get yourself set up for some contributions!

4. Review nweb's math program

Distractions:

Emailed and fb'd early in the day and then one tabbed that away, consider only filling your brain with distractions later in the day as you start to get tired.  Will experiment with this.
Also matcha'd too hard this morning, and the caffine is making you feel sick.  Probably get a travel mug so you don't chug your caffine next time. :p

Neat things:

1. [Article about learning through "play"](https://www.brainpickings.org/2016/08/04/diane-ackerman-deep-play/)

2. A friend had some suggestions:
 * In addition to closing fb/email when programming, I could save checking those for a later, less productive time of the day, so I'm not primed to be thinking about them in the back of my mind while I work.  He estimates this helped his squeeze like 10-15% more out of his day.  He suggests even avoiding fb on the train into work.
 * Sharing your goals with other people is super-helpful.  Seems that in the past, other governments have gotten Americans to inform on each other by starting with writing contests with relatively neutal political themes (eg. "Communism might not make sense in America, but it may make sense in [country]. Discuss.").  Winners would read their essay out loud and share them publicly.  Seems sharing your plans makes you a lot more committed.
 * Doing something that keeps your mind empty during breaks might be helpful.  He uses the [Pomodoro method](https://en.wikipedia.org/wiki/Pomodoro_Technique) and takes 5 minute breaks every 25 minutes, and suggests staring out the window or reading a (non-gripping but light-reading) book for that time.

Notes:

1. Realized that I tend to think of myself as slower than I should be (you're supposed to just wake up and be fabulous, right?) so I tend to assume I will need to grind very hard in silence in order to "catch up" and be accepted by other folks with similar goals as you.  You need to cut this out, it isn't serving you, and is keeping you from setting up positive, motivating habits.

2. Wrote your advanced statistics prof to ask about the logic covered in the course and ask for the text/chapters reviewed so you can review material you have seen before and hopefully jog your memory more quickly back to where you were 8 years ago.

3. Attended License with Confidence at Emacs NYC
 * Shouldn't we just throw it out there because free as in freedom?
 * Publishing gives automatic copywrite
 * Liseance protects you and let's everyone know how you want them to use it
 * Four freedoms (open source) : run, study, redistribute, improve
 * Proprietary (EULA) isn't what we're talking about (they are more restrictive, can run (rarely other three), crazy clauses (itunes at one time said can't build numclear weapon with this))
 * consider: linking, patent claims, distributing, modification, ...
 * apharo : if make mods have to send them upsteam
 * copyright vs copyleft : public domain (can't be copywrited: old books), permissive (MIT, BSD, Mozilla, ISC), weak copyleft (LGPL - using is isnt recissarily derivitive), strong copyleft (GPL, AGPL - if you use any of this code, the whole project becomes this thing, called "the virus" by microsoft)
 * modification: do changes get sent upstream
 * permissive liscenses allowed to be made less premissive later - might need to go back to time when it was less restrictive and use that version, in case of derivitive project can make more restrictive and then people choose which to contribute to 
 * Public domain: Do What The Fuck You Want (just need to change the name when you redistrube), the Unlicense
 * MIT: practically public domain, linking, no warranty, must maintain original license/copywrite
 * BSD: nearly same as MIT, maintail list of contrubtors, 3clases version has non-endorsement clause (cant use who worked on it to sell it), no warranty
 * Apache 2.0: permissive MIT/BSD, requires changelog, clauses for patent release, BSD non-endorsement clause, if you try to patent you can't use the software
 * GPL: beastly license, 2nd most popular to MIT, provides rules to be copyleft
 * GPLv2 (came one year after GPL): cannot sublicense, stong copyleft (linking, modification, distrubution), allows private copies, patent infridgement, not compatible with Apache2.0 (which has more restrictive patent clause)
 * GPLv3: similar to GPLv2, if own hardware need to be able to change the software running on it, allows creation of private copies, allows removal of DRM that is added, prevents Tivoization, prevents patent infridgement
 * Affero GNU Public License: same as GPLv3, fixes application service provider loophole, for network software, no private copies
 * Content licences (video, images, documentations, general authoring...) 
 * GNU Free Document License): similar to GPL, GPL can also be used for docs, restricts use of DRM...
 * Creative Commons: most permissive to view only, based on US legal code (now expanded), all works falling under copyright, not recommended for software, can be combinated to make super-license

## 9/11/2016
### Goals
Overall: 

Think about what core compentencies you need and how to assess what you have. Think also about what chunks tasks should be done and how they can be framed so you can stay focused, motivated and happy.

Ways there:

1. [Khan academy has a diagnostic to find the limits of your math skill](https://www.khanacademy.org/mission/math)
 * Spent about 3 hours getting testing myself up to about a 5th grade level, which was surprisingly fun.  
 * Painfully pulled myself away when I decided it had stopped being fun even though I had the urge hunker down and get as far as I could just to feel go about how far I got.

2. [Learn to be a master-googler](http://www.powersearchingwithgoogle.com/)

Distractions:

I think I'm doing pretty ok here. I was distracted by bacon, why isn't my email filter working, and talking to my friend about learning (which was productive, but I was doing the tab-switching dance).

Neat things:

1. [The blog post I have been wanting to write about leveling up as a beginning programmer](https://www.jagtalon.com/life-after-codecademy-what-do-i-do-now-2/)
2. Recently, a friend suggested I only work on things as long as they are interesting to increase the amount that is actually learned and motivation.  This is surprisingly hard.
3. I filtered MIT-related emails into a folder in my inbox that would bundle and arrive at 7am each morning. I felt like the sky had opened and I was given my freedom or something.

Notes:
