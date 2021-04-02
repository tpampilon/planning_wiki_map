# Wiki Map

A web app that allows users to collaboratively create maps which list multiple "points". For example: "Best Places to Eat Around Town" or "Locations of Movie Scenes".

### Requirements:
* users can see a list of the available maps
* users can view a map
* a map can contain many points
* each point can have: a title, description, and image
* authenticated users can create maps
* authenticated users can modify maps (add, edit, remove points)
* users can favourite a map
* users have profiles, indicating their favourite maps and maps they've contributed to
* use http://leafletjs.com/ or https://developers.google.com/maps/

<!-- User Stories
A user story describes how users will interact with your application

They have the form: As a ___, I want to _, because ____.

eg. As a user, I want to be able to save posts, because I want to review them later.

User stories can also be negated: As a __, I shouldn't be able to _, because ___.

eg. As a user, I shouldn't be able to edit other users posts, because I don't own those posts. ✔️ -->

### User Stories
* As a non-logged-in user, I want to see the list of available maps, because I want to know what kind of maps are there.
* As a non-logged-in user, I want to view an available map and all points on it, because I want to know where specific places are (eg. Restaurants, Groceries etc).
* As a logged-in user, I want to be able to create my own map, because I want to create my own themed maps.
* As a logged-in user I want to be able modify my existing maps, because I want to add or change existing pins.
* As a user, I want to be able to favourite a map, because I want to check it later.
* As a user, I want to be able to have a profile, because I want to be able to view a list of my maps and contribution.

### ERD

!["wiki_map_ERD"](https://github.com/tpampilon/planning_wiki_map/blob/master/ERD/wiki_map_ERD.png?raw=true)