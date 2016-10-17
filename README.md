# MIKB

A repository containing MapBasic / AHK code to create and provide a quickly accessibly MapInfo Knowledge Base for tables in a file system.

## Why?

When working with data, before you can work with your data, you need to understand your data. While working with GIS companies I have often realised that there is so much knowledge about the data in the tables, but often it isn't shared and if it is shared it is in a random word document on the system that you have to go mining for. For this reason, the knowledge is barely ever used, because it is quicker to remain ignorant. Furthermore the knowledge base doesn't expand with new knowledge, because every time you think of something new to add to the document, it takes too long to fish for the folder to write the information down. 

MIKB is here to solve these problems.

## Heard of metadata?

Yes. In fact, Metadata is what I plan to use for this system as well. The difference is, that I assume that some of the files may not be write friendly (they may be read only). In this system we store all information about a table in a completely different folder to their real location, which ultimately protects base tables from alteration.

Finally, it is also capable of opening tables based on their ID. For instance you may have 2 tables:

Layer103 and Layer103_Partial, if setup on ID "Layer###" then both tables will share the same knowledge base. Where as 2 entirely different tables will have 2 entirely different metadata sets.



## Planned Features:

* [ ] Open KB tables upon opening tables (based on ID or Path)
* [ ] Close KB tables upon closing their respective tables (based on ID or Path)
* [ ] User friendly way to set and get the metadata from the KB when needed.
* [ ] Aesthetics using html?
