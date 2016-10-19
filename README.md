# Material Hugo

Material Hugo is a blog theme for [Hugo](https://gohugo.io/).

## Features

- Material & Responsive Design
- Social Share Button
- Pages (e.g. Author Page)
- Categories & Tags
- Code Syntax Highlight
- Google Analytics

## How to use

```bash
hugo server --theme=hugo_theme_material_hugo
```

## Settings

```toml:config.toml
baseUrl = "https://example.com/"
title = "Material Hugo"
theme = "hugo_theme_material_hugo"
googleAnalytics = "UA-xxxxxx-x"

paginate = 10
paginatePath = "page"

[permalinks]
    page = "/page/:slug/"
    blog = "/blog/:year/:month/:slug/"

[taxonomies]
    category = "categories"
    tag = "tags"

[params]
    author = "Your name"
    twitter = "Your Twitter Account"
    github = "Your Github Account"
    facebook = "Your Facebook Page"
    date_format = "2006-01-02 Mon"
```

## Dependencies

- [Materialize](http://materializecss.com/)
- [Prism.js](http://prismjs.com/)

