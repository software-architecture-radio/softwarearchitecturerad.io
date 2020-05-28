---
title: "Episode 2 - Tudor Girba on Solving Problems Without Reading Code"
date: 2017-01-11
draft: false
trackId: "301343971"
trackSlug: "episode-2-tudor-girba-on-solving-problems-without-reading-code"
trackTitle: "Episode 2 - Tudor Girba on Solving Problems Without Reading Code"
---

{{< soundcloud >}}

My guest for this episode is [Tudor Girba](http://www.tudorgirba.com/). Tudor builds tools and techniques for improving the productivity and happiness of software teams. He currently acts as a software environmentalist at [feenk gmbh](http://feenk.com/), a coaching and consulting company that he co-founded.

In 2014 he received the [Dahl-Nygaard Junior Award](http://www.aito.org/Dahl-Nygaard/2014.html) for his work on modeling and visualization of evolution and interplay of large numbers of objects.

He leads the work on the Moose platform for software and data analysis, he initiated the work on the Glamorous Toolkit project for reinventing the software development environments, and he is a board member of the Pharo programming language and environment. He also authored the humane assessment method for making software engineering decisions, and the demo-driven approach to embedding design thinking in software development.

We start out by discussing why simply reading code to solve problems is actually utilizing what Tudor calls an “inhumane assessment” method, similar to how we might say the same about a person plowing a field with their bare hands. When we write code, we’re very often trying to help individuals make decisions by hiding the raw data from them, instead presenting them with a usefully summarized view of those same data. But what do we do when trying to make decisions about our code? We go straight to the data. We read code.

We then get into a conversation about the types of tools that we can build to improve our decision making as developers, tools that Tudor says we should be able to construct in minutes instead of hours or days. Most of the problems we have are search problems. What do we also search quite frequently? A database. How do we do that? We write a query - a query that defines with rich semantics how we want the result to appear. So why don’t we have a query language for code? Why doesn’t the IDE have a query box? The same can be said for architectural problems. And queries are the types of tools we should be able to construct in minutes. We then combine these result sets with powerful visualization tools that allow us to see how our results are clustered together.

The power comes in how cheap these queries are to write, because you’re no longer building with a view toward reuse. Tudor states that “most developers throw away many queries every day,” but that’s only because they are so cheap to write. If your decision making tools for code and architecture had the same economics (relatively cheap compared to their power), then the entire game is changed. And this is the type of environment that Moose strives to create.

After we spend some time talking about how the Moose environment works, we transition into a discussion of detangling monoliths, looking for natural seams in the code. While we’d like to simply just determine what seams the business model should have and decompose from there, very often the code is structured in such a way that the business seams and the natural seams don’t overlap. Sometimes this can stem from a team not having a strong understanding of how they want to model the business. This problems worsens when the business itself doesn’t understand how to model the business.

The conversation then pivots into a discussion of the common motivations behind moving to microservices, and many people say they are seeking modularity. Tudor’s assertion is that they’re really looking for constraints to help them maintain modularity, and that the distributed system model is a high price to pay for those constraints. But if we can write a query of our system’s architecture, we can turn that same query into a test, and that test can become the architectural constraint. And this is exactly the type of tool that Moose provides, in a DSL for architectural constraints.

We close with a conversation about agile architecture. As it turns out, there’s not one architect and several developers, but several architects. And architectural decision making is a commons-based approach. So how do we steer the architecture? And this is where human assessment comes into play, helping us to perform the assessments needed to make appropriate tradeoffs in decision making as a group of architects.

_Audio Notes: roughly 20 minutes into the conversation, there are a few minutes of background artifiacts that we couldn’t isolate from the recording. The same happens around 41:58 with a loud motorcycle just outside where we recorded the episode. We apologize for the poor listening experience._ 

## Links:

* [The Moose Technology Platform](http://moosetechnology.org/)
* [The Moose Book](http://themoosebook.org/)
* [Human Assessment](http://humane-assessment.com/)
* [A set of visual cards explaining the key concepts of Humane Assessment (PDF)](http://humane-assessment.com/res/humane-assessment-on-cards.pdf)
* [A visual slideshow and related links for how architecture cannot be controlled, but can be steered](http://www.humane-assessment.com/blog/emergent-nature-software-systems-slideshow/)
* [A set of case studies showing how various problems got solved. The case studies were done using the Moose analysis platform. (PDF)](http://humane-assessment.com/res/humane-assessment-case-studies-a4.pdf)
* [Engineers should build their own analysis tools and use them to perform effective assessments rather than reading code.](http://www.humane-assessment.com/blog/lets-talk-about-code-reading-teaser-slideshow/)
* [Using Moose to Solve Problems (Video)](http://www.humane-assessment.com/blog/moose-how-to-solve-real-problems-without-reading-code-esug-2014)
* [Software Environmentalism (Video)](https://www.youtube.com/watch?v=KDHrtYGbUQ8)
* [The Glamourous Toolkit - Humane Assessment-centric IDE](http://gtoolkit.org/)
* [Courses on Steering Agile Architecture and Software Analysis](http://feenk.com/)
* [Dave Thomas interview on Software Archaeology](http://www.se-radio.net/2009/11/episode-148-software-archaeology-with-dave-thomas/)
* [Michael Feathers’ book Working Effectively with Legacy Code](https://www.amazon.com/Working-Effectively-Legacy-Michael-Feathers/dp/0131177052)
* [Michael Feathers’ article on Seams in Code](http://www.informit.com/articles/article.aspx?p=359417&seqNum=3)