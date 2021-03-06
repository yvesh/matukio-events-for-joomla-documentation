# Roadmap for Matukio Events

> Please note this roadmap is going to be changed quite often and there is no guarantee for it. 

#### Matukio 5.2

Already released. 5.2.8 probably is going to be the last version 

#### Matukio 5.3

This is a major release, bringing many new features and improvements.

* Event list view (Table)
* Category event list view (Table)
* Joomla registration / login for event registration
* New booking template
* Search for event custom fields
* Filter for event custom fields
* Split dates (e.g. multiple days with breaks etc.)
* Improved statistics
* Option to have no seat / place limitation (e.g. 99999)
* Override certification email in event
* Automatic creation of organizer accounts when used as publisher

Technical changes

* Migration to SQL Schema
* Config settings in config.xml instead of database
* Update TCPDF + Check fonts
* New form Validator for the booking form
* Replace of Bootstrap Modal (too many issues with templates)
* Improved routing (include language)
* Check if email is already registered for guest bookers, if not allowed to book multiple tickets
* Remove + sign on event detail page
* Some more 

Maybe:

* Event Search module (You can already search with Joomla search module)
* Events with a fixed date (open for a fixed date range)
* JSON API for Matukio informations (Joomla! webservice)
* Multiple images with a new image uploader (see Hotspots)
* Automatic discount for buying multiple tickets (Not sure on how to integrate this..)
* New template and theme for the event-list and event 
* Some new modules along with it
* An additional Joomla template (like the one on matukio.compojoom.com)
* Rewrite of the modern template (improved responsiveness, cleanup, but only few design changes)
* Save in Google Calendar button in the event-detail page

### Matukio 5.4

Depends how many features are going to make it into Matukio 5.3, if all above are implemented we are going to skip this version.

* Multi certificate printing
* Share info about event after booking
* Google Calendar integration (Not sure on the details yet)


### Matukio 6

Big release with some major changes

* Complete new form builder for the booking form (Drag & Drop)
* New Event specific fields (With the form Builder) 
* Field sets for events
* Event planer / calendar for organizers / admins
* Archive options and views
* New improved modules