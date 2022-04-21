<p align="center">
    <img src="https://github.com/tariq-abdullah/WP-Air/blob/main/air.png?raw=true" />
</p>

# WP Air - Make your WordPress headless with Static Website generation

Once released, this plugin will help you host your WordPress dashboard and its resulting content(post, pages, custom posttypes) separately. What you get You get is the speediest website possible. 

Normally any wordpress cache plugin is expected to save cache of the pages and serve contents from its cache.  But WordPress still connects to the database at least once even if you use a cache plugin. This makes database a bottleneck for the websites with huge traffic. 

Consider the scenario of a news website. If you get a hundred thousand visitors at once your database requirement, you memory requirement and your processor requirement all shoot up at once. This plugin solves this by simply making a static cache of all the contents of your website. 

## how does this plugin differs from similar plugins

There are some plugins that offer similar functionality but they suffer from either some or all of the following drawback:

  - Don't support selective creation of cache: explained below
  - Complex setup
  - Bad UI
  - No support for comments
  - No support for forms
  - No support for pushing changes to 
  
## selective creation of cache

Let's suppose you have created your initial cache of the content, now when you create a new post, only cache of the new page, home page and category page needs to be updated, not the whole website. (If you are using latest post in the footer then we have to use javascript to load the sidebar from the cache)

as des This way you get faster website with lowest possible 

## Host your site on cloud storage services

This plugin makes it possible for to automatically push changes to cloud storage services like AWS S3, DigitalOcean Spaces etc.

## Other Features

  - Remove Clutter from the code
  - Remove Versions from the CSS
  - Combine CSS Files
  - Combine JS Files
