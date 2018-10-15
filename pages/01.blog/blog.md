---
# http://learn.getgrav.org/content/headers
title: Blog
slug: blog
# menu: Blog
date: 23-01-2013
published: true
publish_date: 23-01-2013
# unpublish_date: 23-01-2013
# template: false
# theme: false
visible: true
summary:
    enabled: true
    format: short
    size: 128
taxonomy:
    migration-status: review
    category: []
    tag: []
# added collection selector
content:
    items: @self.children
    order:
        by: date
        dir: desc
    limit: 5
    pagination: true   


author:
    name: guyadmin
metadata:
    author: guyadmin
#      description: Your page description goes here
#      keywords: HTML, CSS, XML, JavaScript
#      robots: noindex, nofollow
#      og:
#          title: The Rock
#          type: video.movie
#          url: http://www.imdb.com/title/tt0117500/
#          image: http://ia.media-imdb.com/images/rock.jpg
#  cache_enable: false
#  last_modified: true
---

