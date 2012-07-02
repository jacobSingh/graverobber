graverobber
===========

Site structure scraper.

The idea is if you want to make a demo of an existing site in a new system, or build an automated site map you could use this tool to get the heirarchy of pages and their relationship to one another and put it into a structure.

Then one could write extensions to export to different CMSs or wireframing tools.

Example:
--------

I'm bidding on a new project to redo Huffington Post.
<img src="https://www.evernote.com/shard/s83/sh/ad0840a7-a760-41ec-ae85-743aa5902899/e48eeea98926ac8428940a608616b2b8/res/eac06787-9e79-409e-9f65-aedb2ced8572/Breaking_News_and_Opinion_on_The_Huffington_Post-20120702-164745.png.jpg" />

So I run graverobber on it and it pulls down the menus and builds the following:

```
0:
 - Front page
 - Politics
 - Business
 - Entertainment
 - Tech Media
1:
 - Election 2012
 - Celebrity divorce
 - Hispanic Heritage
```

etc, etc.

Then it would be easy to at least clone the structure.

If such a tool exists, please let me know before I build it!

