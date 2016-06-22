# apostrophe-blank-ui
An apostrophe module that removes the default demo UI, giving a blank canvas for front end development.

Normally, after cloning the apostrophe demo site, you're expected to edit the html and css files in the public folder.

I didn't want to do this, I wanted to create interchangeable UI modules (like, "themes") for my sites.

Using this module into an apostrophe installation allows you to not touch the demo code.  It blanks out the content of the site, but
leaves other modules in place so you have admin UI.

It supports the default page types, "default" "home" and "blog".  Add more if you want.

In apostrophe, only sites that have the same "page types" collection can reliably have swappable themes.


1. Copy this module
2. Rename this module to whatever you want
3. Place the folder in lib/modules/ of your apostrophe installation
4. Add a reference to your new module in app.js
5. Recommended: comment out all content in public/css/site.less (assuming you want all content CSS to be controlled from the module)
