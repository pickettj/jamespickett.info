# Personal Academic Website of James Pickett

Modified based on Jekyll template [developed by Ole Vik](https://github.com/OleVik/personal-academic-website).

Useful workflow for two forks of github sites: http://oli.jp/2011/github-pages-workflow/


#### Site settings
The links in the menu, and their order, are edited through `_config.yml`. The format is also nested YAML lists, like the FrontMatter described above. **'baseurl' must be set to your repository (eg. `baseurl: username.github.io`), or the build will fail.** The `name` and `description` variable should also be set, as well as `mathjax: true` if you need to render MathJax formulas on pages.

The `markdown, encoding, locale` variables **should not be changed**.

To find the right page-link (`#somethingonthepage`) you open the page, hover a heading so that the icon-link displays, right-click it and choose "Copy link". Everything after the `#` is the link for this specific title on the page.

Note that these links must be encapsulated in quotes in the lists in `_config.yml`, or they will be interpreted as code-comments.

### Development
Written in [Jekyll](http://jekyllrb.com/), structured with [Bootstrap v4](http://getbootstrap.com/), styled with [plain CSS](http://www.css3-tutorial.net/introduction/what-is-css/). The Jekyll-output (in the `_site`-folder when generated) can be hosted anywhere (static files). For further development, see [Jekyll Tips](http://jekyll.tips/) and [GitHub Pages Setup Guide](http://jmcglone.com/guides/github-pages/).

#### Docker
If you have Docker installed locally, you can start developing locally by cloning your repository to a local folder, and run `docker-compose up` in a terminal. The output will tell you what address to open in your browser.

MIT License 2016-2019 by Ole Vik.
