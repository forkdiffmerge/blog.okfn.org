

## Introducing PyBossa – the open-source micro-tasking platform

 June 8, 2012 in [Featured][1], [Featured Project][2], [OKF Projects][3], [Our Work][4], 
[PyBossa][5], [Technical][6], [WG Open Data in Science][7], [Working Groups][8] 
							

[![PyBossa Logo][9]][10]

For a while now our network has been working on applications, tools and platforms 
for crowd-sourcing and micro-tasking. At the end of last year, [we posted][11] 
about a cute little app developed at a hackday called the [Data Digitizer][11] 
that was being used to transcribe Brazillian budgetary data.

In recent months we’ve been working closely with the [Citizen Cyberscience 
Center][12] on an exciting new platform called [PyBossa][10]. In a nut-shell, 
PyBossa is a **free**, **open-source** **crowd-sourcing** and **micro-tasking 
platform**. It enables people to create and run projects that utilise online 
assistance in performing tasks that require human cognition such as **image 
classification**, **transcription**, **geocoding** and more. PyBossa is there 
to help **researchers**, **civic hackers** and **developers** to create projects 
where anyone around the world with some time, interest and an internet connection 
can contribute.

There is already a wealth of such projects, including long-running ones such 
as [FreeBMD][13] – a huge effort to transcribe the Civil Registration of births, 
marriages and deaths in the UK – as well as more recent ones such as [GalaxyZoo][14] 
– a hugely successful project based on volunteer efforts to classify photographs 
of galaxies taken by the Hubble telescope.

With PyBossa we want to make the creation of such potentially transformative 
projects as easy as possible and so PyBossa is different to existing efforts: 

* It’s a 100% open-source
* Unlike, say, “mechanical turk” style projects, PyBossa is not designed to handle payment or money — it is designed to support volunteer-driven projects.
* It’s designed as a _platform and framework_ for developing deploying crowd-sourcing and microtasking apps rather than being a crowd-sourcing application itself. Individual crowd-sourcing apps are written as simple snippets of Javascript and HTML which are then deployed on a PyBossa instance (such as PyBossa.com). This way one can easily develop custom apps while using the PyBossa platform to store your data, manage users, and handle workflow.

You can read more about the architecture in the [PyBossa Documentation][15] 
and follow the [step-by-step tutorial to create your own apps][16].

## Demos

PyBossa currently comes with several demo applications that showcase two types 
of projects:

* 
**[Flickr Person Finder][17]** and **[Melanoma][18]**: both examples of image classification projects
* 
**[Urban Parks][19]**: an example of a geocoding application

**[Flickr Person][19]** shows how easily you can create a project where you 
have a set of photos or figures that need a classification or a description 
of the photo. In this demo application, the latest 20 published public photos 
from Flickr are used as input for the volunteers where they will have to answer 
a simple question: _Do you see a human in this photo?_

[![PyBossa Baby][20]][17]

The demo project **Melanoma** comes from an idea conceived by a team at [Sage 
Bionetworks][21]. Melanoma is one of the most life-threatening forms of cancer 
and its incidence is on the rise. It is often difficult for medical professionals 
to determine if a skin lesion is cancerous or not, but if diagnosed early patients 
have a 95% chance of survival. Advances in computer-aided image manipulation 
have improved the diagnostic process, but the hope is that the combination 
of these techniques and crowd-sourcing will improve these techniques further 
making early diagnosis more common.

In the demo you are asked to say if a skin lesion shows signs of being cancerous, 
and are taken through the various key questions: _is it asymmetrical?_, _are 
its borders blurred?_, _is its colour uneven?_ and _is it bigger than 6mm in 
diameter?_. The plan is to extend this demo into a project that will help citizens 
recognise the early signs of skin cancer and also enable scientists to evaluate 
the role of crowd-sourcing in medical diagnosis.

[![PyBossa Melanoma][22]][18]

**Urban Parks** is a rather different kind of project. It shows a web mapping 
tool where volunteers are asked to locate an urban park for a given city. The 
goal is to show how web mapping tools can be used to address tasks like geo-locating 
items in a map.

[![PyBossa Urban Parks][23]][19]

If you want to try the demos and PyBossa, go to [PyBossa.com][24] and get clicking. 
If you are interested in the framework you can download the source code from 
the [Github repo][25] and access the documentation [here][15].

## The Future

The focus on PyBossa has initially been on online citizen science projects, 
but it could have important applications in a host of other domains. For one, 
PyBossa could be used to help transcribe handwritten manuscripts of historical 
significance and contribute to existing efforts to make more of our shared 
cultural heritage available for free online and in a structured form.

We have no doubt that there are hundreds of other use-cases for PyBossa which 
we haven’t conceived of yet, and we’re looking forward to seeing the unexpected 
projects that emerge from it.

## Call to action

Does PyBossa sound like something you’d like to get involved in? If so…

* Start [doing some tasks][26]

* Check out and fork the code over on the [PyBossa Github repo][27]

* Join the conversation on the [Open Knowledge Foundation Labs mailing list][28] or ping [PyBossa on Twitter][29]

* Write a new [microtasking / crowdsourcing app][16]

For any questions that you would like to address directly to the development 
team please use info [at] pybossa.com

Related posts:

1. 
[TEXTUS: an open source platform for working with collections of texts and metadata][30] The following post is from Jonathan Gray, Community Coordinator at the Open 
Knowledge Foundation. It is cross-posted from jonathangray.org. Since finally 
blogging about OpenPhilosophy.org last month I’ve been thinking about how one 
could make a generic open source platform that...

2. 
[Introducing our Panton Fellows!][31]   The Panton Fellowships are a new initiative to support scientists who promote 
open access to data. Funded by Open Society Foundations, the Open Knowledge 
Foundation are proud to welcome Ross Mounce and Sophie Kershaw as the first 
ever Panton...

3. 
[Introducing FigShare: a new way to share open scientific data][32] The following post is from Mark Hahnel, founder of the Science 3.0 network 
and member of the Open Knowledge Foundation’s Working Group on Open Data in 
Science. Scientific publishing as it stands is an inefficient way to do science 
on...

 

[← Aid Data: From XML to Visualisations – IATI data in OpenSpending][33]

[Talk at European Data Forum: Open Data, Where We’ve Come From, Where We’re 
Going →][34]

### 1 trackback

* 

##### [В рамках проекта PyBossa подготовлен открытый фреймворк для краудсорсинга | AllUNIX.ru — Всероссийский портал о UNIX-системах][35]

_on June 11, 2012_

Related posts:

1. 
[TEXTUS: an open source platform for working with collections of texts and metadata][30] The following post is from Jonathan Gray, Community Coordinator at the Open 
Knowledge Foundation. It is cross-posted from jonathangray.org. Since finally 
blogging about OpenPhilosophy.org last month I’ve been thinking about how one 
could make a generic open source platform that...

2. 
[Introducing our Panton Fellows!][31]   The Panton Fellowships are a new initiative to support scientists who promote 
open access to data. Funded by Open Society Foundations, the Open Knowledge 
Foundation are proud to welcome Ross Mounce and Sophie Kershaw as the first 
ever Panton...

3. 
[Introducing FigShare: a new way to share open scientific data][32] The following post is from Mark Hahnel, founder of the Science 3.0 network 
and member of the Open Knowledge Foundation’s Working Group on Open Data in 
Science. Scientific publishing as it stands is an inefficient way to do science 
on...

![Avatar of Sam Leon][36]

### Written by   
[Sam Leon][37]

Sam Leon is a London-based Community Coordinator and is the point of contact 
for those looking to get involved in open culture projects at the OKFN. He 
also co-edits the OKFN blog.

[Donate][38]

[Open Knowledge Foundation][39]

* [Log In][40]
* [Sign Up][41]
* 
[Blog Authors][42]

* 
[![Avatar Image][43] admin][44]

* 
[![Avatar Image][45] Rufus Pollock][46]

* 
[![Avatar Image][47] jwalsh][48]

* 
[![Avatar Image][49] ianibbo][50]

* 
[![Avatar Image][51] Jonathan Gray][52]

* 
[![Avatar Image][53] jordanhatcher][54]

* 
[![Avatar Image][55] Friedrich Lindenberg][56]

* 
[![Avatar Image][57] Daniel Dietrich][58]

* 
[![Avatar Image][59] Stefano Costa][60]

* 
[![Avatar Image][61] James Gardner][62]

* 
[![Avatar Image][63] beckyhogge][64]

* 
[![Avatar Image][65] Francis Irving][66]

* 
[![Avatar Image][67] davidjones][68]

* 
[![Avatar Image][69] lisa][70]

* 
[![Avatar Image][71] mhholloway][72]

* 
[![Avatar Image][73] oovrebo][74]

* 
[![Avatar Image][75] saul][76]

* 
[![Avatar Image][77] Sara Wingate Gray][78]

* 
[![Avatar Image][79] timcowlishaw][80]

* 
[![Avatar Image][81] countculture][82]

* 
[![Avatar Image][83] kathryncorrick][84]

* 
[![Avatar Image][85] Guo][86]

* 
[![Avatar Image][87] Jason Kitcat][88]

* 
[![Avatar Image][89] Adrian Pohl][90]

* 
[![Avatar Image][91] Mark MacGillivray][92]

* 
[![Avatar Image][93] psychemedia][94]

* 
[![Avatar Image][95] Nils Toedtmann][96]

* 
[![Avatar Image][97] Stefan Wehrmeyer][98]

* 
[![Avatar Image][99] Theodora Middleton][100]

* 
[![Avatar Image][101] Lucy Chambers][102]

* 
[![Avatar Image][103] James Harriman-Smith][104]

* 
[![Avatar Image][105] Hauke Gierow][106]

* 
[![Avatar Image][107] wwaites][108]

* 
[![Avatar Image][109] Kat Braybrooke][110]

* 
[![Avatar Image][111] Ross Mounce][112]

* 
[![Avatar Image][113] trio3o][114]

* 
[![Avatar Image][115] Mark Brough][116]

* 
[![Avatar Image][117] Robert Harm][118]

* 
[![Avatar Image][119] Velichka Dimitrova][120]

* 
[![Avatar Image][121] Laura Newman][122]

* 
[![Avatar Image][123] Naomi Lillie][124]

* 
[![Avatar Image][125] Joris Pekel][126]

* 
[![Avatar Image][127] Antoine Isaac][128]

* 
[![Avatar Image][129] Pierre-Yves Vandenbussche][130]

* 
[![Avatar Image][131] Sophie Kershaw][132]

* 
[![Avatar Image][133] Chris Taggart][134]

* 
[![Avatar Image][135] Jen Lowe][136]

* 
[![Avatar Image][137] Jonne Catshoek][138]

* 
[Visit][139]

* [Random Member][140]
* [Random Group][141]
* [Random Site][142]

* 

### Meta

				

* [Register][143]
* [Log in][144]
* [Entries RSS][145]
* [Comments RSS][146]
* [WordPress.org][147]

* 

* 				

The content of this site is licensed under a [Creative Commons Attribution 3.0 License][148] (all jurisdictions).   
  
[![Creative Commons License][149]][148]

----

This page was forked with permission from [http://blog.okfn.org/2012/06/08/introducing-pybossa-the-open-source-micro-tasking-platform/][150]

----

[Creative Commons Attribution 3.0 License][148]

[![Creative Commons License][149]][148]

[1]: http://blog.okfn.org/category/featured/ (View all posts in Featured)
[2]: http://blog.okfn.org/category/featured-project/ (View all posts in Featured Project)
[3]: http://blog.okfn.org/category/okf-projects/ (View all posts in OKF Projects)
[4]: http://blog.okfn.org/category/our-work/ (View all posts in Our Work)
[5]: http://blog.okfn.org/category/okf-projects/pybossa/ (View all posts in PyBossa)
[6]: http://blog.okfn.org/category/technical/ (View all posts in Technical)
[7]: http://blog.okfn.org/category/working-groups/wg-open-data-in-science/ (View all posts in WG Open Data in Science)
[8]: http://blog.okfn.org/category/working-groups/ (View all posts in Working Groups)
[9]: http://farm8.staticflickr.com/7217/7350922480_e6f91865d7.jpg
[10]: http://pybossa.com/ (PyBossa Logo by okfn, on Flickr)
[11]: http://blog.okfn.org/2011/11/17/introducing-the-data-digitizer/
[12]: http://www.citizencyberscience.net/
[13]: http://www.freebmd.org.uk/
[14]: http://www.galaxyzoo.org/
[15]: http://docs.pybossa.com/en/latest/overview.html
[16]: http://docs.pybossa.com/en/latest/user/create-application.html
[17]: http://pybossa.com/app/flickrperson
[18]: http://pybossa.com/app/melanoma
[19]: http://pybossa.com/app/urbanpark
[20]: http://farm8.staticflickr.com/7075/7345641190_e20b4c244b.jpg
[21]: http://sagebase.org/info/index.php
[22]: http://farm8.staticflickr.com/7223/7160389541_10f22e40b4.jpg
[23]: http://farm8.staticflickr.com/7096/7160433969_ebe82f8ea4.jpg
[24]: http://pybossa.com
[25]: http://github.com/PyBossa
[26]: http://pybossa.com/app/
[27]: https://github.com/PyBossa/pybossa
[28]: http://lists.okfn.org/mailman/listinfo/okfn-labs
[29]: http://twitter.com/PyBossa
[30]: http://blog.okfn.org/2011/12/20/textus-an-open-source-platform-for-working-with-collections-of-texts-and-metadata/ (TEXTUS: an open source platform for working with collections of texts and metadata)
[31]: http://blog.okfn.org/2012/03/30/introducing-our-panton-fellows/ (Introducing our Panton Fellows!)
[32]: http://blog.okfn.org/2011/03/02/introducing-figshare-a-new-way-to-share-open-scientific-data/ (Introducing FigShare: a new way to share open scientific data)
[33]: http://blog.okfn.org/2012/06/05/from-xml-to-visualisations-iati/
[34]: http://blog.okfn.org/2012/06/12/talk-at-european-data-forum-open-data-where-weve-come-from-where-were-going/
[35]: http://allunix.ru/2012/06/12/%d0%b2-%d1%80%d0%b0%d0%bc%d0%ba%d0%b0%d1%85-%d0%bf%d1%80%d0%be%d0%b5%d0%ba%d1%82%d0%b0-pybossa-%d0%bf%d0%be%d0%b4%d0%b3%d0%be%d1%82%d0%be%d0%b2%d0%bb%d0%b5%d0%bd-%d0%be%d1
[36]: http://www.gravatar.com/avatar/0ee40f9e1964a8a2148babee2e792646?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=50 (Sam Leon)
[37]: http://okfn.org/members/samleon/ (Sam Leon)
[38]: http://flattr.com/thing/605365/Open-Knowledge-Foundation
[39]: http://okfn.org
[40]: http://okfn.org/wp-login.php?redirect_to=http%3A%2F%2Fokfn.org
[41]: http://okfn.org/register/
[42]: http://blog.okfn.org/
[43]: http://www.gravatar.com/avatar/176c4a7af84840c631bc0ac145422e7e?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (admin)
[44]: http://okfn.org/members/admin/
[45]: http://www.gravatar.com/avatar/9a05859ce895e24f593846e0096993d6?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (Rufus Pollock)
[46]: http://okfn.org/members/rgrp/
[47]: http://www.gravatar.com/avatar/03ee965e096697537c19c2c1ce8d72ca?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (jwalsh)
[48]: http://okfn.org/members/jwalsh/
[49]: http://www.gravatar.com/avatar/2827a448159aa5803c49e2a0f4fe671b?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (ianibbo)
[50]: http://okfn.org/members/ianibbo/
[51]: http://www.gravatar.com/avatar/377c62a82666e509ecf5069235199a39?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (Jonathan Gray)
[52]: http://okfn.org/members/jwyg/
[53]: http://www.gravatar.com/avatar/89b2b0b9037ac48a367bda1f9115790b?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (jordanhatcher)
[54]: http://okfn.org/members/jordanhatcher/
[55]: http://okfn.org/wp-content/uploads/avatars/44/52829a540481f03a7e70e6813c421571-bpthumb.jpg (Friedrich Lindenberg)
[56]: http://okfn.org/members/pudo/
[57]: http://www.gravatar.com/avatar/05089b8ca8084550569eb8aeb03a59ec?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (Daniel Dietrich)
[58]: http://okfn.org/members/ddie/
[59]: http://okfn.org/wp-content/uploads/avatars/65/889a55f3e69ec54507bc38cbf3e07794-bpthumb.jpg (Stefano Costa)
[60]: http://okfn.org/members/steko/
[61]: http://okfn.org/wp-content/uploads/avatars/73/49b1f3557209963fe7abf1edf92a1ad6-bpthumb.jpg (James Gardner)
[62]: http://okfn.org/members/thejimmyg/
[63]: http://www.gravatar.com/avatar/f6e828b9bf4e9762a3e28166e655c1de?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (beckyhogge)
[64]: http://okfn.org/members/beckyhogge/
[65]: http://www.gravatar.com/avatar/385f073a12b016d1a85c0fda88ce82d5?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (Francis Irving)
[66]: http://okfn.org/members/francis/
[67]: http://www.gravatar.com/avatar/32196c8ef3d8bff7131e15828c86ca83?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (davidjones)
[68]: http://okfn.org/members/davidjones/
[69]: http://www.gravatar.com/avatar/bb8324edf7e7f982ecc699b5f09336d0?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (lisa)
[70]: http://okfn.org/members/lisa/
[71]: http://www.gravatar.com/avatar/d8ff0f77356b947348155aacc31c4d08?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (mhholloway)
[72]: http://okfn.org/members/mhholloway/
[73]: http://www.gravatar.com/avatar/7c353f16ba276ac8885bea2a574702c2?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (oovrebo)
[74]: http://okfn.org/members/oovrebo/
[75]: http://www.gravatar.com/avatar/c07d4cf37ab8a89c6528f0bcfaddb891?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (saul)
[76]: http://okfn.org/members/saul/
[77]: http://www.gravatar.com/avatar/fe8fcfd3035076aff908b296cecd7472?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (Sara Wingate Gray)
[78]: http://okfn.org/members/sarawingategray/
[79]: http://www.gravatar.com/avatar/b99daa9f050dfdcdc8f207aa3d0ea511?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (timcowlishaw)
[80]: http://okfn.org/members/timcowlishaw/
[81]: http://www.gravatar.com/avatar/b8879a205ee0c96741f97cd4d76297bf?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (countculture)
[82]: http://okfn.org/members/countculture/
[83]: http://www.gravatar.com/avatar/6587635b47e02ea0c7a6dd39da2bd3ac?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (kathryncorrick)
[84]: http://okfn.org/members/kathryncorrick/
[85]: http://okfn.org/wp-content/uploads/avatars/130/9bc51d743697c327ecc31d3842824498-bpthumb.jpg (Guo)
[86]: http://okfn.org/members/guoxu/
[87]: http://okfn.org/wp-content/uploads/avatars/133/166ffe91d739194ac501aaef86ea7930-bpthumb.jpg (Jason Kitcat)
[88]: http://okfn.org/members/jasonkitcat/
[89]: http://www.gravatar.com/avatar/f71df1a4284fc9840e3811085bedec91?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (Adrian Pohl)
[90]: http://okfn.org/members/acka47/
[91]: http://www.gravatar.com/avatar/e6c4b827bd58fb96e506d932ef95d02b?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (Mark MacGillivray)
[92]: http://okfn.org/members/markmacgillivray/
[93]: http://www.gravatar.com/avatar/abbd9f90565ce9ae4d065d93a81d8c03?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (psychemedia)
[94]: http://okfn.org/members/psychemedia/
[95]: http://okfn.org/wp-content/uploads/avatars/157/c480925cd1be3f1154c04108e60ddcdc-bpthumb.jpg (Nils Toedtmann)
[96]: http://okfn.org/members/nilstoedtmann/
[97]: http://www.gravatar.com/avatar/d6ce86ffc1ad91c2d7b79c4a670c3874?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (Stefan Wehrmeyer)
[98]: http://okfn.org/members/stefanw/
[99]: http://www.gravatar.com/avatar/93c81d9ef0d0128ae888e84488604d24?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (Theodora Middleton)
[100]: http://okfn.org/members/theodora/
[101]: http://www.gravatar.com/avatar/48c680a1435659586d2b5fa88978bf2f?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (Lucy Chambers)
[102]: http://okfn.org/members/lucychambers/
[103]: http://okfn.org/wp-content/uploads/avatars/317/8005f55e3b36a3d68a889f526ea8dae9-bpthumb.jpg (James Harriman-Smith)
[104]: http://okfn.org/members/jameshs/
[105]: http://www.gravatar.com/avatar/44ddb1721edfca90f4850de991a551b6?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (Hauke Gierow)
[106]: http://okfn.org/members/hgierow/
[107]: http://okfn.org/wp-content/uploads/avatars/387/8148adbef511b79ef54eb0c14ee2e441-bpthumb.jpg (wwaites)
[108]: http://okfn.org/members/wwaites/
[109]: http://okfn.org/wp-content/uploads/avatars/388/5fbd638e3e4144b79c87376307f25db2-bpthumb.jpg (Kat Braybrooke)
[110]: http://okfn.org/members/katbraybrooke/
[111]: http://okfn.org/wp-content/uploads/avatars/411/4d28444a63771068b6454d671b4dda39-bpthumb.jpg (Ross Mounce)
[112]: http://okfn.org/members/rmounce/
[113]: http://www.gravatar.com/avatar/5fd95c5f0c5b17df29d63d9c842f4a21?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (trio3o)
[114]: http://okfn.org/members/trio3o/
[115]: http://okfn.org/wp-content/uploads/avatars/492/b7c0a9bae5e9b66f1220a49f271d33a3-bpthumb.jpg (Mark Brough)
[116]: http://okfn.org/members/markbrough/
[117]: http://www.gravatar.com/avatar/208a877911b10a56c2548783185ccac9?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (Robert Harm)
[118]: http://okfn.org/members/robertharm/
[119]: http://www.gravatar.com/avatar/540a0e2c2386517f5c464bc214681828?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (Velichka Dimitrova)
[120]: http://okfn.org/members/vndimitrova/
[121]: http://www.gravatar.com/avatar/03d7345ecd2b37c76798693f9d635c06?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (Laura Newman)
[122]: http://okfn.org/members/lauranewman/
[123]: http://www.gravatar.com/avatar/1c06fe54f63fed215caa07bd841969af?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (Naomi Lillie)
[124]: http://okfn.org/members/naomilillie/
[125]: http://www.gravatar.com/avatar/52bbb9ebac4ee33c1a3c4a0479197317?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (Joris Pekel)
[126]: http://okfn.org/members/jpekel/
[127]: http://www.gravatar.com/avatar/e60970252f5a9e59c393b0f2c8b4a338?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (Antoine Isaac)
[128]: http://okfn.org/members/aisaac/
[129]: http://okfn.org/wp-content/uploads/avatars/1519/590806dfce48928ddb09000c76455629-bpthumb.jpg (Pierre-Yves Vandenbussche)
[130]: http://okfn.org/members/pyvandenbussche/
[131]: http://www.gravatar.com/avatar/f5923d49fc13c85bf91c59f7573a9ee6?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (Sophie Kershaw)
[132]: http://okfn.org/members/sophiekershaw/
[133]: http://www.gravatar.com/avatar/cbb0b90a93e3f5033cf8034dc40a9cd9?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (Chris Taggart)
[134]: http://okfn.org/members/christaggart/
[135]: http://www.gravatar.com/avatar/7d8d944e5711e98d74fd698facac9be9?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (Jen Lowe)
[136]: http://okfn.org/members/jenlowe/
[137]: http://www.gravatar.com/avatar/5ef35272bb2d315f8d5f1cbdac3cf6e9?d=http://blog.okfn.org/wp-content/plugins/buddypress/bp-core/images/mystery-man.jpg&s=15 (Jonne Catshoek)
[138]: http://okfn.org/members/jonnecatshoek/
[139]: #
[140]: http://okfn.org/members/?random-member
[141]: http://okfn.org/groups/?random-group
[142]: http://okfn.org/blogs/?random-blog
[143]: http://blog.okfn.org/wp-login.php?action=register
[144]: http://blog.okfn.org/wp-login.php
[145]: http://blog.okfn.org/feed/ (Syndicate this site using RSS 2.0)
[146]: http://blog.okfn.org/comments/feed/ (The latest comments to all posts in RSS)
[147]: http://wordpress.org/ (Powered by WordPress, state-of-the-art semantic personal publishing platform.)
[148]: http://creativecommons.org/licenses/by/3.0/
[149]: http://i.creativecommons.org/l/by/3.0/88x31.png
[150]: http://blog.okfn.org/2012/06/08/introducing-pybossa-the-open-source-micro-tasking-platform/