
# WIKAWORLD

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/800142262?h=f18762786e&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen style="position:absolute;top:0;left:0;width:100%;height:100%;" title="ANIMACJA 1 POKOJ (2)"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

## Introduction

Millennial is a Jekyll theme that was built to be 100% compatible with [GitHub Pages](https://pages.github.com/). If you are unfamiliar with GitHub Pages, you can check out [their documentation](https://help.github.com/categories/github-pages-basics/) for more information. [Jonathan McGlone's guide](http://jmcglone.com/guides/github-pages/) on creating and hosting a personal site on GitHub is also a good resource.


## Configuration

### Sample Posts

Visit the [the demo site](https://lenpaul.github.io/Millennial/) to find sample posts that show what different types of text formatting look like. You can find these posts in the `_posts` folder, which show what the best practices for setting up your own site are.

### Site Variables

To change site build settings, edit the `_config.yml` file found in the root of your repository, which you can tweak however you like. More information on configuration settings and plugins can be found on [the Jekyll documentation site](https://jekyllrb.com/docs/configuration/). This is also where you will be able to customize the title, description, and the author/owner of your site.

If you are hosting your site on GitHub Pages, then committing a change to the `_config.yml` file will force a rebuild of your site with Jekyll. Any changes made should be viewable soon after. If you are hosting your site locally, then you must run `jekyll serve` again for the changes to take place.

In the `settings.yml` file found in the `_data` folder, you will be able to customize your site settings, such as setting Disqus comments, Google Analytics, what shows up in your menu, and social media information.

### Adding Menu Pages

The menu pages are found in the `menu` folder in the root directory, and can be added to your menu in the `settings.yml` file.

### Posts

You will find example posts in your `_posts` directory. Go ahead and edit any post and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention of `YYYY-MM-DD-name-of-post.md` and includes the necessary front matter. Take a look at any sample post to get an idea about how it works. If you already have a website built with Jekyll, simply copy over your posts to migrate to Millennial.

### Layouts

There are two main layout options that are included with Millennial: post and page. Layouts are specified through the [YAML front block matter](https://jekyllrb.com/docs/frontmatter/). Any file that contains a YAML front block matter will be processed by Jekyll. For example:

```
---
layout: post
title: "Example Post"
---
```

Examples of what posts looks like can be found in the `_posts` directory, which includes this post you are reading right now. Posts are the basic blog post layout, which includes a header image, post content, author name, date published, social media sharing links, and related posts.

Pages are essentially the post layout without any of the extra features of the posts layout. An example of what pages look like can be found at the [documentation page](https://lenpaul.github.io/Millennial/pages/documentation.html).

In addition to the two main layout options above, there are also custom layouts that have been created for the [home page](https://lenpaul.github.io/Millennial/) and the [contacts page](https://lenpaul.github.io/Millennial/pages/contact.html). These are simply just page layouts with some [Liquid template code](https://shopify.github.io/liquid/). Check out the `index.html` file in the root directory for what the code looks like.

### YAML Front Block Matter

The recommended YAML front block is:

```
---
layout:
title:
author:
categories:
tags: []
image:
---
```

`layout` specifies which layout to use, `title` is the page or post title, `categories` can be used to better organize your posts, `tags` are used when generating related posts based on the topic of the post, and `image` specifies which images to use. Have a look at some posts in the `_posts` directory to see how these variables are set.

## Features

### Disqus

Millennial supports comments at the end of posts through [Disqus](https://disqus.com/). In order to activate Disqus commenting, set `disqus.comments` to true in the `_data/settings.yml` file. If you do not have a Disqus account already, you will have to set one up, and create a profile for your website. You will be given a `disqus_shortname` that will be used to generate the appropriate comments sections for your site. More information on [how to set up Disqus](http://www.perfectlyrandom.org/2014/06/29/adding-disqus-to-your-jekyll-powered-github-pages/).

### Google Analytics

It is possible to track your site statistics through [Google Analytics](https://www.google.com/analytics/). Similar to Disqus, you will have to create an account for Google Analytics, and enter the correct Google ID for your site under `google-ID` in the `settings.yml` file. More information on [how to set up Google Analytics](https://michaelsoolee.com/google-analytics-jekyll/).

### Syntax Highlighting

Millennial provides syntax highlighting through [fenced code blocks](https://help.github.com/articles/creating-and-highlighting-code-blocks/). Syntax highlighting allows you to display source code in different colors and fonts depending on what programming language is being displayed. You can find the full list of supported programming languages [here](https://github.com/jneen/rouge/wiki/List-of-supported-languages-and-lexers). Another option is to embed your code through [Gist](https://en.support.wordpress.com/gist/).


## Questions?

This theme is completely free and open source software. You may use it however you want, as it is distributed under the [MIT License](http://choosealicense.com/licenses/mit/). If you are having any problems, any questions or suggestions, feel free to [tweet at me](https://twitter.com/intent/tweet?text=My%question%about%Millennial%is:%&amp;via=paululele), or [file a GitHub issue](https://github.com/lenpaul/Millennial/issues/new).

