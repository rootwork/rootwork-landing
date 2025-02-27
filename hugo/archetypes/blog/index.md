---
title: '{{ replace .Name "-" " " | title }}'
author: ivan
date: '{{ .Date | dateFormat "2006-01-02" }}'
# lastmod: '{{ .Date | dateFormat "2006-01-02" }}' # Appends 'edited on' to the publish date

slug: '{{ .Name }}' # Recommended length is 3 to 5 words.
# aliases:

# For the post as it appears in lists.
summary: >
  Summary

# For SEO and social media snippets (recommended 150-200 characters).
description: >
  Description

draft: true # Change to 'false' to publish this post.
disable_feed: false # Change to 'true' to exclude from RSS etc.
unlisted: false # Change to 'true' to exclude from search, lists, sitemaps, and feeds.
# priority: '1.0' # Override the sitemap priority for this post, range 1.0 (high) to 0.0 (low)

featured: false
toc: false

showDate: true
showReadTime: true
showShare: true

# menu: main

# featureImage: 'feature.jpg' # Top image on post.
# featureImageShade: true # Add a translucent shade to the image to make overlaid text easier to read.
# featureImageAlt: 'Description of image' # Alternative text for featured image.
# featureImageCreditFlickr: 'username'
# featureImageCreditCustom: 'Top image credit Flickr user [username](https://www.flickr.com/photos/username).'
# thumbnail: 'thumbnail.jpg' # Image in lists of posts.
# shareImage: 'share.jpg' # For SEO and social media snippets. Falls back to thumbnail (if set) or featureImage.

codeMaxLines: 10 # Override global value for how many lines within a code block before auto-collapsing.
codeLineNumbers: false # Override global value for showing of line numbers within code block.
figurePositionShow: false # Override global value for showing the figure label.
showRelatedInArticle: false # Override global value for showing related posts in this series at the end of the content.

series: # Creates lists of posts in series as well as custom tag.

categories:
  - frontend development
tags:
  - Drupal
keywords: # Extra keywords in addition to the above, for SEO.

# Archive taxonomy terms (auto-generated)
year: '{{ .Date | dateFormat "2006" }}'
month: '{{ .Date | dateFormat "2006-01" }}'
---
