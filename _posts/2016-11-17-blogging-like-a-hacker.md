---
layout: post
title: "Blogging like a hacker"
---

I was amazed by the idea of static site generators for quite sometime already, recalling the times when knowing HTML and CSS was actually enough to build a web-site. So trying to serve my own page with [Jekyll](https://jekyllrb.com/) was on my to-do list since I finished my studies last month.

What was stopping me from doing it sooner was Ruby Jekyll is built with and lack of time to start learning it now. Luckily, you don't really need to know the language to blog with Jekyll, the installation process is well documented and there are plenty of [blog topics](https://www.smashingmagazine.com/2014/08/build-blog-jekyll-github-pages/) describing all the different development options you have.

OS X actually has Ruby installed already but I've read that it has some quirks related to System Integrity Protection that makes installing Jekyll tricky, so the easiest way to do it is with [Homebrew](http://brew.sh/) running:

```/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"```

Then, to install Ruby:

```brew install ruby```

And, lastly Jekyll:

```sudo gem install jekyll```

After that, just choose if you want to build your site from zero making your own theme or use one of the [free available ones](http://jekyllthemes.org/) and customizing it to your needs as I did, fill your site with content and push to GitHub.

And don't forget to [refresh your Markdown syntax](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code) knowledge as you'll need it to write the posts.

Happy blogging!
