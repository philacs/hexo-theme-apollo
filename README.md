Hexo theme: Apollo
=================

**This hexo theme is modified from SANOGRAPHIX.NET**

[Original](https://github.com/sanographix/tumblr/tree/master/apollo) (Tumblr theme)
[Demo](http://joyceim.github.io/hexo-theme-apollo)

##Installation

###Install

``` bash
$ git clone git@github.com:joyceim/hexo-theme-apollo.git themes/apollo
```

**Apollo requires Hexo 2.4 and above.**

###Update

``` bash
cd themes/apollo
git pull
```

##Configuration

``` yml
# Header
menu:
    Home: /
    Archives: /archives
rss: /atom.xml

# Content
more_link: true
fancybox: true

# Miscellaneous
google_analytics:
favicon: /favicon.png
```

- **menu** - Navigation menu
- **rss** - RSS link
- **more_link** - "Read More" link at the bottom of excerpted articles. `false` to hide the link.
- **fancybox** - Enable [Fancybox](http://fancyapps.com/fancybox/)
- **google_analytics** - Google Analytics ID
- **favicon** - Favicon path
