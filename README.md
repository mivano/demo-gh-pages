# demo-gh-pages

Start by creating a new jekyll site by using the codespace and executing:

`jekyll new blog`

Then navigate to the `blog` folder and serve the site

`jekyll serve`

This should build and start the website on a port which can be opened

Go to the _posts folder and add a new `.md` file, add this as contents:

```markdown
---
title: Hello!
layout: post
---

# Hi there 👋

```

See that is dynamically refreshes

Commit the newly created pages

Go to GitHub, settings, pages and see that there is a workflow.

The action should build and deploy. It will output a location to find the site.

Add more pages, or alter the _config file to see the effects.