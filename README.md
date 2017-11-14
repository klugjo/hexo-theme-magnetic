# Magnetic Blog Hexo

![](http://www.codeblocq.com/img/hexo-theme-thumbnail/Magnetic.png)

Hexo implementation of the free [HTML5 Magnetic Template](http://pixelhint.com/magnetic-free-html5-responsive-photography-website-template/)

Magnetic is a photography/design portfolio oriented, responsive theme. [Demo here](http://www.codeblocq.com/assets/projects/hexo-theme-magnetic/).

## Features Overview

- Disqus and Facebook comments
- Google Analytics
- Cover image for posts and pages
- Tags Support
- Responsive Images
- Image Gallery
- Social Accounts configuration
- Pagination

## Not Supported

- Post Categories will not be displayed
- Posts and Pages Dates not displayed anywhere 

## External libraries used

- [FeatherLight.js](http://noelboss.github.io/featherlight/) (Gallery)
- [jQuery](https://jquery.com/)

## Installation

```
$ git clone https://github.com/klugjo/hexo-theme-magnetic themes/magnetic
```

Then update your blog's main `_config.yml` to set the theme to `magnetic`:

i.e:

```
# Extensions
## Plugins: http://hexo.io/plugins/
## Themes: http://hexo.io/themes/
theme: magnetic
```

## Theme Configuration

The theme's global configuration is done in `/themes/hexo-theme-magnetic/_config.yml`.

### Menu

The menu is configured in the theme's `_config.yml`.

```
# Header
menu:
  Home: /
  Archives: /archives
```

The object key is the label and the value is the path.

### Default post title

The default post title (used when no title is specified) is configured in the theme's `_config.yml`.

```
# Default post title
default_post_title: Untitled
```

### Default index page cover image

You can specify a default thumbnail for posts on the index page (Home page). This image will be used if you forget to specify an image in the post's front matter.

```
# Default post cover index page
default_cover_index: "http://placehold.it/450x450"
```

### Default post page cover image

You can specify a default thumbnail for posts/pages on the post/page page (Detail Page). This image will be used if you forget to specify an image in the post's front matter.

# Default post cover index page
default_cover_detail: "http://placehold.it/1300x500"

### Favicon

You can specify the favicon.

Example:
```
# Favicon
favicon: "/img/favicon.ico"
```

### Comments

The comments provider is specified in the theme's `_config.yml`. If you specify both a `disqus_shortname` and a `facebook.appid` there will be 2 sets of comment per post. So choose one.

```
# Comments. Choose one by filling up the information
comments:
  # Disqus comments
  disqus_shortname: klugjotest
  # Facebook comments
  facebook:
    appid: 123456789012345
    comment_count: 5
    comment_colorscheme: light
```

### Google Analytics

The Google Analytics Tracking ID is configured in the theme's `_config.yml`.

```
# Google Analytics Tracking ID
google_analytics:
```

### Social Account

Setup the links to your social pages in the theme's `_config.yml`. Links are in the footer.

```
# Social Accounts
twitter_url:
facebook_url:
behance_url:
googleplus_url:
dribble_url: 
rss_url:
```

## Post Custom Configuration

For each post, you can specify additional information in the [front matter](https://hexo.io/docs/front-matter.html)

### Post's Index Thumbnail

Use `cover_index` to specify an image that will be used for that post on the Home page (also knows as index)

Example:

```
cover_index: /assets/work1.jpg
```

### Post's Detail Thumbnail

Use `cover_detail` to specify an image that will be used for that post on the Detail page for that post.

```
cover_detail: /assets/hero_image.jpg
```

## Creator

This theme was created by [Pixel Hint](http://pixelhint.com/) and adapted for Hexo by [Jonathan Klughertz](http://www.codeblocq.com/).

## Bugs

If you have a question, feature request or a bug you need me to fix, please [click here](https://github.com/klugjo/hexo-theme-magnetic/issues/new) to file an issue.