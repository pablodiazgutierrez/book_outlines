#Coders at Work -- by Peter Seibel

This book is a collection of extensive interviews with prominent programmers. The topics covered range from their earliest interest in the art and craft of programming, how they work, what they consider important and what they have learned during their heralded careers.

Common questions in most interviews:
* What was your first program you remember writing?
* How do you go about designing software? Top down or bottom up?
* What is your desert island list of books for programmers?
* Do you consider yourself a scientist, engineer or craftsman? Or somethig else entirely?
* Have you read Knuth's "The Art of Computer Programming"?
* What do you think about (Knuth's) literate programming?
* How do you identify programming talent?

One recurring answer to the question of identifying talent is to pay attention to their ability to write in plain English (or whatever their native language might be). I tend to agree with this sentiment, based on my experience working with others. Programming is a collective effort, and being able to express your ideas in a way that is understandable by others and yourself from the future is extremely valuable. I find it difficult to believe that someone might write code with great clarity and brilliance, yet be unable to speak cogently about it.

### Jamie Zawinski (Netscape, Lisp/Xemacs, DNA Lounge)
* Actually got paid at some point to program Lisp
* Favors quick and dirty over well done because if you take too long, someone will eat your lunch (at least if you're doing it for money)
* Not interested in TDD, because it gets in the way of writing faster (see previous point)
* Wrote Netscape's first email client
* Hates design patterns and people who promote them (blames them for Netscape's demise)
* Co-founded Mozilla foundation, worked on browser refactor, then rewrite and moved on to open DNA Lounge after getting disillusioned
* Still writes screensavers for fun (they're neat little throaway programs you don't need to plan for, because there's no point in reusing much of them)

### Brad Fitzpatrick (Livejournal, Google)
* Jack of all languages hacker, wrote LiveJournal as a fun side project that took a life of its own as friends kept using it
* Conceived seminal ideas like DB sharding and scalable web architectures
* Favorite hiring question: "given 2 arbitrarily long integers as a decimal string, multiply them." Lots of possible answers some of them terrible.

### Douglas Crockford (JSON, Yahoo JS architect)
* Found XML too complicated, proposed JSON instead
* Vocal critic of making JS more complicated (as designed in ECMAScript 4)
* The problem of JS is that the web architecture has become so successful that it's hard to make it better without breaking what's working
* Microsoft has the same problem since they need to keep backward compatibility with such crappy old systems, even though their new stuff is good.
* Still, we're all better off without Corba, XML and other committee driven alternatives
* Big advocate of group code reviews. Each week, one person is responsible for printing out their going over their code and walking the group through each line. After a while, you get used to not taking the critiques personally.
* "An hour of code reading is worth two weeks of QA"
* Quotes [Exodus 23:10](https://www.biblegateway.com/passage/?search=Exodus+23:10-12) as an analogy: One out of each 7 sprints should be spent cleaning code. Otherwise you end up with an unmaintainable system.
* Write software knowing that you're going to throw much of it away, in parts, so keep it flexible and replaceable
* Prefers Eiffel over C++, among other things, because it supports pre-post conditions explicitly
* Computing has moved back. We had things like timesharing, marketplaces, sandbox security and more which we lost with the arrival of the PC
* Advice for self-taught programmers: Read a lot
* Got into computing because he thought it could make the world a better place, but is disappointed so far in the small impact the open web has had. Perhaps social systems take time to evolve on top of technical improvements?

### Brendan Eich (creator of JavaScript, Mozilla)
* Created JavaScript in 10 days, knowingly taking too many shortcuts
* Tried to fix it with ECMAS 4, but found opposition to the added complexity that would break backward compability

### Joshua Bloch

### Joe Armstrong

### Simon Peyton Jones
* Hoare principle: *"There are two ways of constructing a software design: One way is to make it so simple that there are obviously no deficiencies, and the other way is to make it so complicated that there are no obvious deficiencies. The first method is far more difficult. It demands the same skill, devotion, insight, and even inspiration as the discovery of the simple physical laws which underlie the complex phenomena of nature."*
