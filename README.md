# MeegsPedia

Allows user to view and edit an encyclopedia of entries. Uses Markdown to write the contents of the pages.


## Design Document

Required HTML-files to use MeegsPedia:
create.html
edit.html
entry.html
error.html
index.html
layout.html
search.html

No sketch but best possible description of how to use:
On the home page you are greeted with a list of all the current pages registered in the encyclopedia. These entries are all hyperlinks to their respective page. On the left we have a sidebar including a search bar, home-button (which links to the index page), a "create a new page" button, which allows the user to create a new entry. And a "random page" button, which links to a random existing page from the registered entries. The search bar allows you to search for certain pages. If your search entry is a valid page, you get redirected to that page. If your search entry is present in the name of an existing page, you get a list of all the pages that contain your search entry. If there is no page containing your search entry, you get a message there are no results for your entry and you get a link back to the home page to see the entire list of current pages. If you click on an existing page, you can edit the title and contents of that page. This is done with Markdown. If you click save on this page, the entry is saved in the dataset of this wiki. If you press "Create New page" in de sidebar you can add your own page to the dataset. You can add your own title and content. This is also done using Markdown. Once you click "submit your entry" it is permanently saved in the dataset, and you can view it on the home page and search for it using the search bar.

Sketches are in "Sketches" Folder in the repository above.
