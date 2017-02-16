Material theme plugin for Kanboard
==================================

This plugin override core templates and use template hooks to create a custom theme.
The CSS I started out with was from some forum and was meant for putting in the limited custom CSS box of Kanboard.
When the box could not hold the stuff I wanted, or by then, needed badly, I downloaded the theme example and put everything in that instead.
Credits should go to the person who wrote the original CSS for Kanboard but this is work in progress so I will write more here later on.
I put this here on github for easy deployment after having to adjust my CSS after upgrading from Kanboard 1.0.37 to 1.0.39.

- New CSS styles are added with the hook **layout:head**
- A top bar is added to the layout by using the hook **layout:top**
- The header template is replaced by a new one with a template override

Installation
------------

What I think will work:

- go to your kanboard installation **plugins** folder
- git clone this repo
- rename the project folder to **Theme**
- m a g i c

Original instructions:

- Create a directory **Theme** under the folder **plugins**
- Copy all source files in this new directory
- Go on your local installation of Kanboard
- After the login, you should see the alterations to the default layout

Screenshot
----------

![plugin-example-theme](screenshot.png?raw=true)
