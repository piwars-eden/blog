# piwars eden blog

## Getting started

### Prerequisites

Install Hugo:
`brew install hugo` if you've got homebrew, if not then try following the information on the [gohugo website](https://gohugo.io/getting-started/installing/)

### Working locally with the blog
With the repository `git clone` it to a specific directory.
Then `cd` into that folder.

You'll need hugo installed and then run `hugo server` which will start the server on `http://localhost:1313`

Visit the blog in the browser and you'll be able to see it.

### Adding a post

Add a post to the `content/post/something-something.md` with the following header:
```
+++
showonlyimage = true
draft = false
image = ""
date = "2019-11-20T00:00:00+00:00"
title = "Foo"
writer = "Bar"
categories = [ "baz"]
weight = 1
+++
```
