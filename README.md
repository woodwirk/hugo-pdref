# Hugo Lithium Refs

This theme is intended to make it easier to keep track of notes you take while reading digital content. In addition to searching all of your notes, you can see all of the images associated with your notes/references in one place.

It's based on the following:
- [@jrutheiser/hugo-lithium-theme](https://github.com/jrutheiser/hugo-lithium-theme) (original theme)
- [@yihui/hugo-lithium](https://github.com/yihui/hugo-lithium) (modifications for blogdown/R)
- [@woodwirk/hugo-lithium-search](https://github.com/woodwirk/hugo-lithium-search) (offline search based on Fuse.js)

## Additional Features

- Image dictionary (based on PhotoSwipe)
- Note that while this theme is based on one made for blogdown, it can be used like a regular [Hugo](https://gohugo.io/) theme

## License

The original hugo-lithium-theme was released under [the MIT License](https://github.com/jrutheiser/hugo-lithium-theme/blob/master/LICENSE.md), as were the subsequent revisions. This version is released under the same license. Please see the attributions for more information.


---
# Hugo Lithium

A simple responsive blog theme for [Hugo](https://gohugo.io/) forked from https://github.com/jrutheiser/hugo-lithium-theme with modifications to make it work better with [**blogdown**](https://github.com/rstudio/blogdown).

The easiest way to get started is to create a new (empty) RStudio project, then

```r
devtools::install_github('rstudio/blogdown')  # install blogdown
blogdown::new_site(theme = 'yihui/hugo-lithium')
```

Then you should be able to see an example website launched in the RStudio Viewer.

For the full documentation, please see this section in the **blogdown** book: https://bookdown.org/yihui/blogdown/themes.html

## Features

- Blog
- Responsive
- Disqus
- Google Analytics
- Google web fonts (Merriweather and Lato)
- MathJax
- highlight.js


