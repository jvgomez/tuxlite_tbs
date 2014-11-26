# tuxlite_tbs #

Originally taken from: https://github.com/getpelican/pelican-themes

Not forked because I do not want all the other themes in the repo.

My version with the following fixes:

- bootstrap-collapse.js is served locally so now the collapse button works perfectly. Related with this issue: https://github.com/getpelican/pelican-themes/issues/126
- jQuery version updated so Chrome does not complaing about unsafe scripts.
- Added support for tables of contents.
- Since better-figures-and-images Pelican plugin only works with rst files, I have included the CSS settings to use them in embedded HTML in the Markdown files.
- Github-like code syntax highlighting from https://github.com/richleland/pygments-css
- Google Analytics template changed.
- Other minor fixes

## Screenshot ##

![screenshot](screenshot.png)
