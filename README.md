# wikipedia-game
Wikipedia game - Give it the starting URL, end page href whose path you want to find, the bot will go online and find the path for you.
View the Jupyter notebook in Python for demo code.

Example - 

start_page_url = "https://en.wikipedia.org/wiki/United_States"
end_page = East_River

Output - 'United_States' -> 'New_York_(state)' -> 'East_River'

The bot will find the shortest path between this start page on WikiPedia till the end page.

It is implemented as graph algorithm (BFS). Beautiful Soup library with lxml parser is being used. This library can be installed with pip.
The code is in Python 3. 

Assumption - The path exists.

Modification you can make - 
Instead of ending page href, or finding href you can tweak the code to read the value instead of href.

Have fun!
If you have any questions, contact me on - 
www.mithunjmistry.com
