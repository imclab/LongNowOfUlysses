#Hansen (s)Log 


##3 April

Today was breakthrough day. Yesterday, JS and the UVic Help Desk provided me with the mod for the .htaccess file that would allow me to access PHP 5 on the UVic server. Stupidly, when I edited the file, I wiped the original content which controls permalinks, killing two of the three pages on my localhost. Whoops. I Googled permalink code for Wordpress today, replaced the content, and reestablished my links (thank dog). 

However, I was faced with this message when I attempted to go to my site on the UVic server:

![database error](http://imageshack.us/a/img835/60/picture1osr.png)

I tried to edit my wp-config file with info from the UVic server, but not totally understanding how MySQL works, I wasn't sucessful. So, I turned to my new friend Brendan at the Help Desk. After some back-and-forth re: authoring databases, etc., Brendan advised me to use my own database.

![email](http://imageshack.us/a/img256/491/picture3idv.png)

I checked this email tonight after work, at which time the help desk was closed. Being a bit of a pitbull, I didn't want to let this sit until tomorrow. I exported my wordpress database from MAMP and found/replaced the local urls with my new live url. I had an .sql file and nowhere to put it. What next? Google. I found a tutorial that said -- and this is so painfully obvious to me now -- that I need to access phpMyAdmin for my new server. I googled "uvic phpmyadmin" and found this:

![phpmyadmin](http://img542.imageshack.us/img542/1506/picture5ih.png)

I tried several times to login with my Netlink, and was unsuccessful. After trolling through some HCMC blog posts relating to UVic's phpmyadmin, I saw that the username is actually uvic\Netlink, and there is no password. And there I was in phpMyAdmin. I don't have the privilege to set up a new database, but I was able to import my wordpress database.

![database](http://imageshack.us/a/img819/308/picture2bnj.png)

After diddling around with possible info in my wp-config file, I finally have a live sit at http://web.uvic.ca/~ahansen/ulyssesafterlives. I am so excited. 

![UlyssesAfterlives](http://imageshack.us/a/img251/4148/picture4rk.png)


##30 March

Now that my UlyssesAfterlives page is up and running wonderfully on my local server, I tried once more to clear out the old webpage on my university webpage. I managed to delete the old material, and replace it with my Wordpress files. Finally, an index:

![index](http://img191.imageshack.us/img191/7573/picture6ku.png)

Unfortunately, when I click on my Wordpress site on the index, this happens:

![old PHP](http://imageshack.us/a/img42/4540/picture5ea.png)

I hope to get in touch with someone at the Helpdesk or something to see if I can sort this out. I know that the MVP site runs Wordpress on the UVic webspace, and that the Maker Lab site will run on it as well. Not sure what's going on here -- is my access limited because I am a student? We'll see. 

Another thing I am increasingly interested in is the way in which my project trajectory has functioned almost as a translation of data to fit into one "language" (expression) or another. Interesting.  

Oh, and I now know how to link thumbnail images from Imageshack, where I store all of my goods, thanks to my wonderful friends on the Internet. I still have some misgivings about the elitist assumptions built into digital work (DH is the hockey of humantities -- a lot of people would be really great at it if they could afford the gear), but I do not for a second doubt the democratic nature of the web. Before starting this work, I knew literally nothing about MySQL, Apache, or PHP, Filezilla, local servers v. remote servers, etc., and I have fumbled my way through with the help of kindly souls in forums (fora?) and chat rooms like this one:

![forum](http://imageshack.us/a/img507/834/picture4li.png)


I hit Google pretty hard for anything -- I can't stand not knowing things. In the past, I have fixed faucets and furnace control panels using advice from forums, but I have never used the Internet to help me do things on the Internet to this extent. I am really excited about my expanded knowledge and skill set. 


##28 & 29 March

This has been a *very* eventful couple of days. After finally committing to TimelineJS, I have been trying to develop my project interface. This has not been without its trials -- tech-spec related, as usual. However, this time it is not my computer that is out of date, but rather UVic's web hosting (PHP is too old for Wordpress 3.5.1).

First, I made the mistake of thinking I could set up a simple Wordpress.com blog as a project interface. I soon learned that neither Java nor embedded codes are allowed in Wordpress.com blogs. So, I decided to give my UVic webspace a try. 

This makes me laugh: remember when Bethany Nowviskie brought up memoranda of understanding regarding web maintenance? At the time, I thought of my long-deactivated (I thought) UVic website that I hastily made in 2008 using Nvu. And a shiver ran down my spine at the thought that anyone might see my really bad site. Well, I went to web.uvic.ca/~ahansen, and this is what I saw:

![Ms.Hansen's Webpage](http://imageshack.us/a/img32/8237/picture1wd.png)

Yep. My neglected Tamagochi. I took at a look at the files using Filezilla, and it was a hot mess. Thus, I decided to go back to my friend(s) MAMP to set up a Wordpress.org database and site on my local server for now. After my exposure to MAMP when setting up Omeka to run Neatline (#fail), I encountered little trouble creating an interface for my project where I can embed my timeline, and also include the context of my timeline, as I have not found that timelines in general are all that conducive to the kind of critical perspective I want to bring to the translations of *Ulysses*. 

![Wordpress](http://imageshack.us/a/img442/4197/picture2te.png)

The really exciting part for me is seeing the timeline in all it's glory, embedded in my UlyssesAfterlive Wordpress site. And it looks gooood. 

![timeline](http://imageshack.us/a/img341/1310/picture3yks.png)


##23 March

Good news: Google spreadsheet has sorted itself out. However, I am no longer content with using GE or Maps. Because Neatline (my preferred option) is out of the running for good, I am having to forsake the timeline aspect of my look at *Ulysses* translations. That is no good. I have tried to create a path to my points in Google Earth, but it is not effective. I am not at all happy with the aesthetic or function. So, I have decided to scrap the map, and opt for the timeline instead. 

###My New Interface

I will now be using TimelineJS for UlyssesAfterlives

![TimelineJS](http://imageshack.us/a/img255/2396/picture6cf.png)

This is actually really exciting. I saw Timeline in action via LD's project, and I was and am impressed by the app's aesthetic. The timeline transitions really smoothly, and it seems to allow various media with few problems (unlike GE, which wouldn't display my images). 

####Interoperability -- A Nice Surprise

Because Timeline renders spreadsheet data, I was able to copy and paste some of my existing data from Spreadsheet Mapper to my new JS sheet. This is saving me so much trouble! 

![new data set](http://imageshack.us/a/img4/4097/picture7mr.png)
![my timeline](http://img707.imageshack.us/img707/864/picture3ee.png)

What I have so far looks wonderful, and Timeline seems to be running really smoothly. Also, I am using a screen shot of my Google Map (literally hours and hours in the making) in the timeline, so all of that learning and prep work was not wasted. 


##22 March

I have been trying to work on my spreadsheet for Google Earth/Maps, but I can't generate a KML file -- Google says I am running too many scripts simulaneously for my account. 

![Google error](http://imageshack.us/a/img577/1976/picture5sx.png)

I Googled it, and so far one other person has reported that error (on StackOverflow), but no one has answered. I am pretty much crippled by that error at this point.  

##19 March

Neatline isn't working for me. I managed to set up a local server, run Omeka 1.5 (minimum requirement for Neatline), and install the Neatline plugin. However, it did not show up on my dashboard. 

![Neatline dashboard](http://imageshack.us/a/img341/4424/picture4xic.png)

JS offered to set up a sandbox on his website, but that too fails to show the plugin. I must make another choice, and soon. 


##16 March

I have decided -- after seeing [Neatline](http://neatline.org) in action at Bethany Nowviskie's workshop -- to give installing Neatline a try. Having never done anything like this, it has ended up being quite dramatic. 

###My Neatline installation workflow:

####Neatline's workflow:

![Neatline workflow](http://imageshack.us/a/img849/333/picture1lsw.png)

####My guides:

![Omeka forum](http://imageshack.us/a/img839/5092/picture3nt.png)

####MAMP installed: 

![MAMP](http://imageshack.us/a/img208/4072/picture6hb.png)

####Filezilla:

![Filezilla](http://img820.imageshack.us/img820/4278/picture9ij.png)

####My Omeka main page:

![Omeka main page](http://imageshack.us/a/img585/7030/picture5bt.png)

####All of the screens:

![all the screens](http://imageshack.us/a/img687/6374/picture2ap.png)


##14 March

###Bethany's Visit

That Bethany Nowviskie is a cool lady. She is so approachable, but also -- clearly -- very knowledgeable. I really appreciate her realistic approach to grad education and DH. 

A couple of things that stood out to me:

* the UV memoranda of understanding re: DH project -- I was reminded of the 90s digital pet sensation, where it does nothing, but you have to feed it or it will beep. No one wants their work to turn into that. 

* CVs v. résumés -- thank you, Bethany! A CV is not a professional résumé. 

Bethany's talk today made me want to pursue a PhD in DH just so that I can work at UV in her lab. 


##12 March

Today was Bethany Nowviskie's [Neatline](http://neatline.org/) workshop. I thought Neatline was cool before -- after checking out the website when I was debating which application to use for UlyssesAfterlives. Now, I am hooked. My plan is to give the installation process a try to see if I can install a MAMP version that is new-old enough a) for my computer to run, and b) to be able to host Omeka.

###Of Note

Bethany said that Neatline purposely does not have the capability to set up a sequence and play them. The narrative underlies the exhibit, and the developers want users to play around. I hear that -- my concern with Google Earth/Maps is that if I don't create a sequence to play, no one will get any sort of narrative, and my exhibit will just be a bunch of bubble on a map. 


##5 March

###Feedback on First Draft

###What do you think of the project in Google Earth v. Google Maps?

LD: The flat map (GoogleMaps) is much easier to look at--it's clean. I find the topographical map in GoogleEarth to be distracting and I assume unnecessary information for your project. There is more contrast in maps. 

The flattened map, from my perspective gives a much better sense of the way that these iterations of the texts are clustered together/concentrated in one area. 

TD:	Preferred Google Earth over Google Maps -- sick of it. Too unacademic? 
	

###Should I attempt to make an animation, or should users interact with map by navigating through the bubbles?

LD: Can you do both? It would be nice to have an animation that visualizes the way Ulysses has migrated around the globe open up as soon as people visit your website--it could also include a brief instructional portion that will show readers how to navigate the map and make them aware of the kind of information they can gather from it--without being overtly instructional. 

TD:	Animation would be cool. Depending on what you are prioritising that might be a good extension. 


###How much information should I include in each bubble? Keep it short, or give a comprehensive context (if possible)?

LD:	Keep the preview short, but it would be nice to a drop-down box/link that offers more information.

TD:	Bubbles will look good -- expect to see a significance of the placemark/edition. 


###Reflection

I will definitely be creating a short video/animation which communicates a narrative stream (using slides, images, etc.). Right now, my project looks like a bunch of bubbles on a map -- it needs context and interpretation. 


##4 March

Working on some final touches for my first iteration. Interim report reminded me that I have not been uploading my log updates into GitHub. I keep them saved on my desktop in an .md file, but I have been admittedly remiss in updating my GitHub log. That all changes now. 

Also really looking foward to seeing what everyone has on the go for tomorrow!


##3 March

I have a rough bubble template down now, and I am becoming more happy with it as I play around. The next step in my workflow is to plug in the data I have been collecting. After we go over our first drafts on Tuesday, I will begin to sort out my info into colour-coded bubble, with a view to having them move in a sort of sequence. 

![bubble template](http://imageshack.us/a/img841/6128/uliss.png)

###Issues

One issue I am having -- and which TP brought up last class, I think -- is putting images into my bubbles. Text is no problem so far, but I don't know where to host my images so that they can be pulled into Google Maps. I have uploaded a couple onto my Google Drive and made them public, but Google Earth doesn't seem to understand the link... I will chat with TP and see what he has found re: images. 


##1 March

Success! I have figured out -- via diddling around (how I learn) -- both where to find a decent bubble template, and also how to change around the code. This is big news for me. 

![bubble template](http://imageshack.us/a/img705/8114/picture6mq.png)
![code](http://imageshack.us/a/img59/3476/picture5bkt.png)


##27 February

Google Earth continues to challenge me with bubble format, so I have been working for now in Google Maps. Aesthetically, this does not please me, but I am using it to gauge my info as I go. Over the next couple of days I will attempt to look into the bubble code for Google Maps. 

![Google Maps](http://imageshack.us/a/img266/9789/basicmapp.png)


##20 February

I am continuing to research a bit -- the SUNY website continues to be ridiculously useful. Also, I am struggling a bit to get beyond the basic format for the bubbles. Google seems to separate Google Earth from Spreadsheet Mapper 3.0, which means that I see things I like in Google Earth, but can only make them happen manually at this point (no thanks). 

![Google options](http://imageshack.us/a/img547/4979/earthvspreadsheet.png)

I will continue to look around, as that is how I work best. 


##13 February

After discussing projects in yesterday's seminar, I have decided to refine a narrative for my map, rather than just plunk points down. Based on the research I have done up to now, it seems that the obscenity trial and fear of censorship dictated the way in which *Ulysses* moved across the globe, and also, I am guessing, how it was adapted for screen and stage. Therefore, I am going to create a series of layers that differentiate partial translations or publications from full translations and publications in an attempt to track the parts and the whole of *Ulysses*. I will also create separate layers for stage/film adaptations, and other media adaptations -- such as [ULYSSES SEEN](http://ulyssesseen.com/). 

Feeling more focussed already. 


##11 February

I deleted a template and could not get it back when I was playing around with my data model, so I have copied and pasted info into a new spreadsheet. I have learned my lesson: just don't delete things. 

![My new data model](http://imageshack.us/a/img594/4774/datamodelsm3.png)

Will continue sourcing material for map. I happened upon a [SUNY Buffalo exhibit](http://library.buffalo.edu/pl/exhibits/joycebloomsday/caseXII/index.html) that chronicles some of the translations of *Ulysses* -- it seems a good place to start (will give me the chance to accumulate some easily accessible data before moving on to film adaptations and theatrical productions). 

![SUNY exhibit](http://imageshack.us/a/img827/8058/sunyj.png)


##9 February

Have the data model link via prompt (not email -- thanks, JS!). 

Even though I am not there yet, data-wise, I decided to see if I have Google Earth on my laptop. Yes, it turns out, I do. Date modified? 28-Jan-09 -- it's been a while. Opened GE and everything is working well (which is a relief, given my aged laptop's inability to cope with most programs). 

I have managed to create modify a template, create some sample data, and visualize sample KML file in GE. 



###Some Issues

1. There is something strange going on with my template sheet and GE: my data is not showing -- just the title. 
2. I retrieved latlong from GE by locating address info I have from a source -- once KML transfers back to GE, the point are not where they should be (Düsseldorf, Germany in the middle of the English Strait?). 

Will continue to work with data model to figure out quirks -- so far, it looks promising. 


##5 February

JS has suggested both a data model for using Google Earth, and also a means of creating an animation of the map: screen shots edited into a short film. Simple, right? Sounds perfect to me -- iMovie and the like I know well enough to make that happen. 

The data model for Google Earth looks really approachable, which is a relief. I am excited to get some of my sample data into the spreadsheet -- will do once JS provides link to the model. 


##4 February

JS has strongly advised against using Flash -- I will defer to his judgment (apparently Google Earth can do something equally cool with less difficulty on my part). We will discuss it more in class tomorrow, so I will hopefully have a more concrete plan, and be able to move into data collection as per my Needs Assessment timeline.

In the comments on the NA, JS also questioned my workflow for the project -- I will figure that out once I know my program and how to proceed (next week?).  


##26 January

In response to my Thought Piece, JS suggested that Neatline might not be the best option because of its academic aesthetic and operability. Therefore, I am thinking that I might attempt to create an animated map using Flash. I have never used Flash before, but my former Grade 8 students could do it rather effortlessly (and not the tech-savvy kids, either), so I should be able to figure it out...

Right now, I envision a short animation that populates a world map with different iterations (translations, film adaptations, etc.) of Ulysses. The points will be annotated with info about the iterations, effectively showing the spatial and temporal influence of Ulysses across the globe. 


##25 January

Unfortunately, I think olfactory is out because of the campus's no-scent policy -- that raises the question of bureaucratic influence on artistic expression. Also, this makes me question the space itself: what exactly will we be able to accomplish in this space if sound and scent are limited? Will we be able to create an intelligent environment? Is an alcove in a quiet study area the ideal venue for an exhibit on the continuing influence of modernism, which by definition celebrated disruption?

I admit that I am beginning to feel the possibility of disappointment regarding what we will be able to do. My fear is that digital elements -- my map, for example -- will be relegated to an "online component," thereby perpetuating the divide between the digital and the analogue. Sad. Face.  


##22 January

I love the idea of the relational in an exhibit -- like reader response in a museum/gallery environment. This is why I am still eager to incorporate smell into the exhibit. Apparently, the sense which connects most closely with memory and emotion is smell (and Joyce was into all of the senses). This isn't new -- see John Harris's 1979 essay ["Oral and Olfactory Art"](http://www.jstor.org/discover/10.2307/3331746?uid=3739400&uid=2129&uid=2&uid=70&uid=3737720&uid=4&sid=21101797393497) -- but it is also avant-garde in the art scene -- see New York's Museum of Art and Design.

![olfactory art](http://imageshack.us/a/img842/9524/olfactory.png)


##21 January

I've made my first major change -- and it's groundbreaking: I'm using Firefox. Although I have staunchly opposed Firefox in the past (until last week) because of it's PC-aesthetic, I am trying to get used to it. 

Also, I am playing around with ideas for my project, which I know I want to involve mapping. Right now, I am thinking Neatline, even though I am not familiar with the program, nor is my laptop able to run it. Given the busyness of the Maker Lab these days, Neatline might not be a wise choice because of limited access to adequate infrastructure. I will investigate further after the Thought Piece presentations and before working on my Needs Assessment. 



