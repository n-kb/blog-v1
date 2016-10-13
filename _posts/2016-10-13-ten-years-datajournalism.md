---
layout: post
title: "Celebrating 10 years of datajournalism"
category: posts
---

_This essay was written for my talk at the MINDS conference in Copenhagen, on 20 October 2016._

Datajournalism is turning 10! The starting point has been set (by me) to September 2006, when Adrian Holovaty published his oft-quoted piece [A Fundamental Way Newspapers Websites Need to Change](http://www.holovaty.com/writing/fundamental-change/), which serves as a manifesto for many datajournalists.

Datajournalism means doing journalism with structured data. Because working with structured data requires strong computer skills, datajournalism mostly means journalists working together with computer developers. This combination of skills enabled all the datajournalism projects you heard of, from the Wikileaks Cablegate to the Panama Papers.

Before I reflect on what datajournalism has achieved and look whether or not newspapers websites changed in a fundamental way, let's go back to the beginnings of datajournalism, in a small town, in rural America<sup><a name='note_1' href='#foot_1'>1</a></sup>.

### It all starts in Kansas

In the early 2000's, a 20-something named Rob Curley was employed at the Topeka Capital Journal. He was in charge of online publishing. It wasn't much of a prestigious job. A the time, less than a quarter of Americans went online regularly. The strategy of most newspapers on the internet was to re-publish print articles online, usually after they had been printed. 

Of course, things were already moving. The 1998 Starr report, which gave the details of the Clinton-Lewinsky affair and was published online, had shown that online users could access source documents without the filters of editors<sup><a name='note_2' href='#foot_2'>2</a></sup>. The 2001 attacks had shown that publishing online first and print second might make sense. Most media people did not understand what these changes meant, but Rob Curley did.

Curley understood that a website was not a clone of a newspaper on a screen. He understood that you could serve information and content to different audiences much more effectively than in print. He offered users free email and wallpapers (this was 2002!) and pioneered trends that proved more long-lasting. He built a database of all records for the local sports teams, going back to their creation in the late 19<sup>th</sup> century. After every game, his team would add new statistics on each players<sup><a name='note_3' href='#foot_3'>3</a></sup>. He also pioneered new formats, such as interactive maps. In 2004, for the 50<sup>th</sup> anniversary of the _Brown v. Board of Education of Topeka_ decision, which declared segregation in schools illegal in the United States, the Journal published an interactive map, where users could click on dots to see more information<sup><a name='note_4' href='#foot_4'>4</a></sup>. It sounds very unremarkable, until you realize that Google Maps did not even exist at the time (it was launched in 2005)<sup><a name='note_5' href='#foot_5'>5</a></sup>.

Rob Curley left the Topeka Capital Journal in 2002 and moved 40 kilometers to Lawrence, Kansas, to work at the LJ World. There, he hired Adrian Holovaty, a self-taught programmer and journalism graduate who had worked at the online operation of the Atlanta Journal-Constitution<sup><a name='note_6' href='#foot_6'>6</a></sup>. The team at the LJ World had developers and journalists working hand-in-hand. They replicated what worked at the Topeka Capital Journal and brought it to a whole new level.

To give you an idea of the kind of work they did, let me quote at length from a job offer they posted in 2004<sup><a name='note_7' href='#foot_7'>7</a></sup>:

>If you're in the online media field, or trying to get into it, this is the place to be for innovation.

>From a content perspective, we pride ourselves on being hyper-local, converged across multiple media (TV, newspaper, Web) and focused on overkill. This is the type of place that doesn't just cover little-league baseball games with a story or two in the Sunday paper; it devotes an entire print publication and Web site to it, with **cell-phone updates**, **weblogs** and **intensive team/league/field databases**.

>Our Web-news operation relies heavily on custom development; **pretty much everything is built in-house**. The small-but-nimble development team handles everything technical for our network of sites. **We're the people our newsroom comes to** for implementing special features and workflow optimizations, and we're the people the online boss comes to for building the frameworks for new sites and subsites.

The emphasis is mine. It shows that the LJ World worked at the cutting-edge of technology (in 2004, blogs and SMS alerts were a novelty) and that they were working _with_ journalists, not in a separate IT section.

At the LJ World, Curley and Holovaty built a new content management system (CMS) because they felt the current one was not good enough. In the process, they created the [Django](https://en.wikipedia.org/wiki/Django_(web_framework)) framework, which is now a very popular tool to build and maintain websites. It is used by the likes of Instagram and Pinterest, which you wouldn't expect to use a tool that came out of a newsroom.

### Spreading over the world

The pioneering work of Holovaty and Curley did not go unnoticed. Publishers were already flying to Topeka in 2002 to see Curley's team from close up. The reluctance of newsrooms to work with developers slowly ebbed away. 

In Europe, the wake-up call came in June 2010, when Wikileaks published the Afghan War Diaries. Wikileaks shared a database of exclusive reports from NATO troops in Afghanistan with Der Spiegel, the New-York Times and the Guardian. It also published most of the source database online, in SQL format. In most European newsroom, no one had a clue how to open such an SQL file. Many realized that, had they had a developer in-house on that day, they could have broken new stories.

That's what the company I worked in at the time, OWNI.fr, did. Because we were journalists working hand-in-hand with developers, we did publish some stories and interactives based on the Afghan documents. This got the attention of French publishers, who started to build their own datajournalism teams.

Since 2010, dozens of datajournalism operations were created. They are everywhere: at local newspapers like Le Télégramme de Brest (France) or Heilbronner Stimme (Germany), at national newsrooms like Nu.nl (Netherlands) or El Mundo (Spain) and at broadcasters like Yle (Finland) or Český rozhlas (Czechia)<sup><a name='note_8' href='#foot_8'>8</a></sup>.

More importantly, datajournalism works. It works for investigations, as the Panama Papers showed. Süddeutsche Zeitung, which received the leak, had to hire a datajournalist (Vanessa Wormer) to better cope with the documents. It works for traffic, too. Pieces from the datajournalism team routinely top the most-viewed rankings of news websites<sup><a name='note_9' href='#foot_9'>9</a></sup>.

The European conference on datajournalism, Dataharvest, grew tenfold from its creation in 2010 and now brings together hundreds of specialists. The American equivalent, NICAR, grows from year to year. Specialized conferences emerge, such as Tapestry (for storytelling) in the United States or NODA in the Nordics. Academics now study datajournalism as a field in itself.

Journalism schools have also integrated datajournalism to their curriculum. Students now receive ECTS credits in datajournalism course. That scraping data and coding can contribute to students receiving degrees in journalism is a considerable achievement. Some schools even have specialized postgraduate programs, such as the [Máster en Periodismo de Investigación, Datos y Visualización](http://www.escuelaunidadeditorial.es/masteres/master-en-periodismo-de-investigacion-datos-y-visualizacion) in Madrid. The platform we built to teach datajournalism, jQuest, is in use at over 20 schools, just one month after launch!

All this growth and appetite for datajournalism is reason enough to celebrate. However, the "fundamental change" Holovaty argued for in his article ten years ago did not happen.

### No fundamental change

Ten years is not a short amount of time. You might feel as young as you were in 2006, but keep in mind that 10 years is all it took for  cinema to grow from a technical curiosity to the industry we know today. Hollywood studios, the star system, movie theaters and feature films all appeared in the first decade of the twentieth century. If datajournalism had the potential to fundamentally change the news industry, it could have done so in the past ten years.

In his landmark article, Holovaty argued that news organization should move from an article-centric worldview, where every piece of information is stored in big blobs of text (the articles), and move to a data-centric one, where different pieces of information are stored separately. By storing structured data instead of text, news organizations could re-purpose a piece information after is has been published. It made business sense then, as it does now. (If the difference between an article-centric and a data-centric organization isn't clear to you, do read [Holovaty's piece](http://www.holovaty.com/writing/fundamental-change/) in full).

In 2002, exactly when Holovaty and Curley were creating databases of sports results in Lawrence, Kansas, a small European company was doing pretty much the same thing. That company was called SportingStatz and worked exactly like the journalists of the LJ World did: Whenever a game was played, they collected a lot of data and used it to create visualizations of the game, provide readers with detailed reports and a valuable archive. SportingStatz changed its name to Opta Sports and is now the world leader in sports data. It was acquired in 2013 for about €50 million<sup><a name='note_10' href='#foot_10'>10</a></sup>. The LJ World was also acquired recently, for an undisclosed sum. Upon buying the company, the new owner fired a third of the staff<sup><a name='note_11' href='#foot_11'>11</a></sup>. While Opta grew to world dominance, the LJ World shrunk into irrelevance.

Why did two company that did the same thing 14 years ago have such different fates? Maybe it is simply a question of corporate culture. 100-year-old organizations such as newspapers might have a hard time nurturing fast-growing activities. Despite having developed a CMS and one of the most popular web frameworks under Holovaty, for instance, the LJ World failed to turn it into a profitable venture and exited the business in 2012<sup><a name='note_12' href='#foot_12'>12</a></sup>.

In Holovaty's 2006 piece, most of the links to the project he showcased are dead. When it comes to his work at the Washington Post, _all_ of the links are dead. Can corporate culture also explain such a disregard for archives?

Blaming culture is the lazy thing to do. It does not explain why a certain corporate culture would fail to nurture two successful business and jettison work it paid dearly to produce. The reason why newspapers did not embrace datajournalism, why they did not fundamentally change their websites, to paraphrase Holovaty's title, lies somewhere else. It lies in the purpose newspapers give themselves.

### The change that did happen

Holovaty's article was built on the assumption that newspapers are "essential sources of information for their communities". While this might have been true in the early 2000's, it isn't today. To check the weather, you probably have a widget on your phone (or just trust Facebook). To check on events, you probably use Meetup or Ticketmaster (or Facebook). Movies? Rotten Tomatoes (or Facebook). Dates? Tinder (via Facebook Connect). New album from your favorite band? Spotify (or Facebook).

Most of our essential sources of information now lie outside of newspapers. Of course, all these competitors structure their data. Otherwise, they could not provide us with powerful search features, automated alerts and tailored offers. Facebook's dominance, for instance, is due in large part to its ability to structure information about its users and put them into very specific groups that advertisers can target. Not a single company that aims at being an essential source of information would think for even a second to store information in blobs of text. Not a single company, except news outlets.

Let's recap. Newspapers want to be essential sources of information. Essential sources of information must store their information as structured data. Newspapers know how to store information as structured data, but do not do so. The only possible explanation to this conundrum is that newspapers relinquished their mission to be essential sources of information for their communities.

That newspapers give up on their role as providers of essential source of information is only normal. Ever since their creation in the early modern period, newspapers have carried several missions: Provide information, publish opinions and debates or demand change through hard-hitting investigations. We tend to think of these missions as a bundle, because the technology and economics of content ensured that whoever provided one provided the other two.

Digitization allowed for each mission to be conducted separately more easily. This was not lost on publishers. Some of them (such as Axel Springer, Schibsted or Le Figaro in Europe) understand that it makes a lot of sense to create subsidiaries to provide essential information on verticals where business models are easy to find. Platforms providing job, housing or car classifieds are largely owned by traditional publishers. For other verticals, such as politics, crime or road accidents, the same publishers did not choose to pursue their role of providers of information. Instead, they focused on discussion and opinions, for which blobs of text are great<sup><a name='note_13' href='#foot_13'>13</a></sup>.

Holovaty's life story is here again enlightening. After the Washington Post, he created a company that provided structured data at the micro-local level, EveryBlock.com. The company was acquired by MSNBC in 2009, which simply killed it four years later. Tellingly, EveryBlock wasn't shut down because it was unprofitable, but because _it didn't fit with the owner's strategy_<sup><a name='note_14' href='#foot_14'>14</a></sup>.

***

In the last ten years, datajournalism became a great resource for some investigations and enabled new forms of storytelling that users love. Meanwhile, structured data transformed the classified industry and let Facebook take over most online conversations. Some websites did change in a fundamental way, as Holovaty argued. It just wasn't newspapers'.
	

<h4>Newsletter</h4>
<p>In case you want to read my next essay in your e-mail inbox, type you email below and you'll be all set.</p>
<form style="padding:3px;" action="https://tinyletter.com/nkb" method="post" target="popupwindow" onsubmit="window.open('https://tinyletter.com/nkb', 'popupwindow', 'scrollbars=yes,width=800,height=600');return true"><p><label for="tlemail">Enter your email address</label></p><p><input type="text" style="width:300px" name="email" id="tlemail" /></p><input type="hidden" value="1" name="embed"/><input type="submit" value="Subscribe" /></form>


 <a name='notes' ></a>

### Notes 



<a href='#note_1' name='foot_1'>1.</a> This entire history of datajournalism is made of white dudes in their 20's. It's likely that I'm missing out on contributions from others, being myself a white dude in my 20's at the time. If you think I should mention someone, do tell me so: hi@nkb.fr


<a href='#note_2' name='foot_2'>2.</a> For more on how the Starr report impacted the media ecosystem, read [Sept. 11, 1998: Starr Report Showcases Net’s Speed](https://archive.is/20161013/https://www.wired.com/2009/09/dayintech_0911starrreport).


<a href='#note_3' name='foot_3'>3.</a> An archived version of this database can be [found at the web Archive](https://archive.is/20161013/Catzone http://web.archive.org/web/20020901144026/http://catzone.com/data/womensbasketball/2001_2002/teams/619_stats.shtml).


<a href='#note_4' name='foot_4'>4.</a> Still [online here](https://archive.is/20161013/Historic map http://cjonline.com/indepth/brown/historic-spots-map.shtml).


<a href='#note_5' name='foot_5'>5.</a> For more background on Curley's work at the Topeka Capital Journal, read [Innovation in the Heartland](https://archive.is/20161013/http://www.ojr.org/ojr/lasica/1029874865.php), a 2002 piece of the Online Journalism Review.


<a href='#note_6' name='foot_6'>6.</a> You'll find a nicely written portrait of Holovaty at the Chigaco Tribune: [EveryBlock's Adrian Holovaty can't find "individuality or entrepreneurship" in the news business](https://archive.is/20161013/http://featuresblogs.chicagotribune.com/technology_internetcritic/2008/08/everyblocks-adr.html)


<a href='#note_7' name='foot_7'>7.</a> Find the job application on Holovaty's blog: [Job: Web developer for World Online in Lawrence, Kansas](https://archive.is/20161013/http://www.holovaty.com/writing/280/).


<a href='#note_8' name='foot_8'>8.</a> I started compiling a list of all datajournalism operations in Europe [on an Etherpad](https://archive.is/20161013/https://public.etherpad-mozilla.org/p/Datajournalism_Teams_in_Europe). The total count is over 50.


<a href='#note_9' name='foot_9'>9.</a> [The World at 7 Billion](https://archive.is/20161013/http://helenesears.co.uk/?projects=the-world-at-seven-billion) was the most shared news story on Facebook in 2011, for instance. A dialect quiz at the New-York Times [was the most-viewed article of 2013](https://archive.is/20161013/http://www.wbur.org/hereandnow/2014/02/19/vaux-dialect-quiz). The list could go on.


<a href='#note_10' name='foot_10'>10.</a> Read [Perform Group buys sports data company Opta](https://archive.is/20161013/http://www.reuters.com/article/perform-opta-idUSL5N0F90L520130703).


<a href='#note_11' name='foot_11'>11.</a> Read [30 people elminated at LJWorld](https://archive.is/20161013/http://6lawrence.com/news/local-news/19709-30-people-elminated-at-ljworld).


<a href='#note_12' name='foot_12'>12.</a> Read [The Lawrence Journal-World gets out of the CMS business, losing out to freebies like WordPress](https://archive.is/20161013/http://www.niemanlab.org/2012/06/the-lawrence-journal-world-gets-out-of-the-cms-business-losing-out-to-freebies-like-wordpress/). The LJ World did not sell Django, which is free. Instead, it sold Ellington, a CMS based on Django. The economics of open source software are complex and not the focus of this essay. What must be noted, however, is that most companies that manage successful open source software do have a business around it, through sales of services, certification, conferences etc.


<a href='#note_13' name='foot_13'>13.</a> It's important to note that many organizations do provide structured information on these other verticals. In politics, Regards Citoyens in France or VoteWatch.eu at the European level do just that. Even though many journalists within newspapers would love to launch such projects, very few attempts were made.


<a href='#note_14' name='foot_14'>14.</a> Read [NBC closes hyperlocal, data-driven publishing pioneer EveryBlock](https://archive.is/20161013/http://www.poynter.org/2013/nbc-closes-hyperlocal-pioneer-everyblock/203437/). While the financials of EveryBlock have never been made public, NBC said it wasn't _profitable enough_, not that it was bleeding money. For the 5-year-old project that EveryBlock was at the time, such an achievement is already a financial success.
