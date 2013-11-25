Template Notes Module
==========================

Adds a "Help" tab to pages for notes and instructions on the current template used.

You can add content by simply putting a file in /templates/notes/ the module will automaticly load that file if it find one and adds a "Help" tab to pages edit form.

Name the files using the template name. You can use html or markdown to write the help text.

- /site/templates/notes/[tplname].html
- /site/templates/notes/[tplname].md

To style the content you can specify a custom css file url you add to the module settings.

