# item-catalog-website
This is a python project that creates a website and JSON API for a list of items and their catalog.Authenticated users can edit or delete items they've creating. Adding items, deleteing or editing items require you to login in with Google+ or Facebook. You can still view the item catalog without login but you have no permission to add a new item to the catalog.

## Technical Specifications

1. Frontend : Bootstrap, HTML5, CSS.
2. Backend : Flask web framework (Python).

## Instructions to run:
### Setup The database and start the server:

1. In the root directory run Git Bash / Terminal
2. Run "pyhon database_setup.py" this will create the database with the categories defined in database_setup.
3. Populate the database using "python lotsofmenus.py"
4. Run "python project.py" to start the server.

### You can assess the website by typing http://localhost:5000/ in your browser
