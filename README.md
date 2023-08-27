# NoSQL-Challenge
Eat Safe, Love – Module 12
For the ‘Eat Safe, Love’ project, MongoDB is used to create a NoSQL data repository.  Data consisting of food hygiene ratings of a variety of food vendors is provided by the JSON file “establishments”.
This data is imported and analyzed with the construction of the following two Python programs via a Jupyter Notebook platform:
1)	NoSQL_setup.ipynb 
2)	NoSQL_analysis.ipynb

New libraries and tools are utilized, including PyMongo, Pretty Print (pprint), and the $rejex operator.
The backdrop of the project being that of the work of a UK Food Standards Agency food consultant, on assignment for food magazine “Eat Safe, Love”, is intriguing.  It allows for a ‘friendly’ setting on which to explore the somewhat intimidating and complex concepts involved in the establishment of a Mongo Client, and the building of a NoSQL database.  Note, this additional attention to curriculum detail is very much appreciated by a programmer who hails from the somewhat ‘antiquated’ less-dimensional coder’s world.  A world where often the analyst would not need to engage a command window, and devise text to import data directly from the terminal, as in our case:

$ mongoimport --type json -d uk_food -c establishtments --drop --jsonArray establishments.json

This text literally gives birth to the NoSQL database ‘uk_food’ and it’s collection ‘establishments’. For, as I have learned in this module, NoSQL database technology stores information in JSON documents instead of the columns and rows that form the architecture of the traditional relational database (i.e. SQL).  This, of course, points to the prefex ‘No’ of our acronym— referring to ‘not only’ SQL (and not to be erroneously confused with ‘no’, as in ‘none at all’).  In contrasting sentiment, the assignment was more than substantive, nourishing the pertinent knowledge for which data science students crave 😊.

