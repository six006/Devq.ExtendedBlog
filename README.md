# Devq.ExtendedBlog

Demo:
http://sapias-solutions.nl/Profile/admin


This Orchard module contains features for an extended blog. This includes:

- Multiple authors for items with the AuthorablePart attached (by making use of the ContentPickerField)
- Display authored items with the author content type
- Display weighted tags of the items which are authored by the author content item


!! IMPORTANT !!

Because this module defaults to attaching the AuthorPart to the User content type, the module Contrib.Profile should be installed first to see the new features in the user content type.
Though you can also just create a new content type 'Author' and attach the authorpart to that content type.

The Contrib.Profile module can be found here: https://orchardprofile.codeplex.com/


# Setting options

AuthorablePart options:
- Automatically assign the current logged in user to the newly published content item (Only works if the AuthorPart is assigned to the User content type)

AuthorPart options:
- Maximum number of tags that will be displayed with the author (defaults to 10, 0 for all)
- The display type of the authorable items
