NYTimes Crossword Data
=========

This is a CSV dump of collected data representing clues and answers from The New York Times crossword over almost 16 years.

It spans `October 1996` through to `December 31st 2012`. The data was first collected for a small project to build a [search engine][se] with it. The `clues.txt` files is about 13.1MB in size and contains 432,205 clues with answers.

[se]: http://donohoe.io/projects/crossword/#/git

Data
-----


The data is a tab-delimited CSV with the columns (omitted), in this order:

    CLUE    ANSWER    YEAR    MONTH
    
For example:

    Held by a third party  INESCROW	00	2
    "Private on-line chats, for short"	IMS	00	2
    """Ah, Wilderness!"" character ___ Miller"	NAT	00	2
    "War zone, in brief"	ETO	00	2
    Places for mending	SANITARIA	00	2
    Legion of Honor member	CHEVALIER	00	2
    Noodle-and-vegetable soup	RAMEN	00	2

Alternative source:
- [https://docs.google.com/file/d/0BzysYYjJHCE5Tk9SU2tkSUdnUGc/edit][gd]

[gd]: https://docs.google.com/file/d/0BzysYYjJHCE5Tk9SU2tkSUdnUGc/edit

Gaps
-----

There may be gaps in the data. 2006 is missing. Nothing amazing happened in 2006 anyway (not counting Edmund Phelps winning Nobel Peace prize for Economics).

To do
-----

- Recover 2006.
- Re-insert day, full-date
- Across/Down, Clue Numbers (there were enough discrpencies that made it better to ommit than include)
