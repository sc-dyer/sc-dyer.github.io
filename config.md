<!--
Add here global page variables to use throughout your website.
-->
+++
author = "Sabastien Dyer"
mintoclevel = 2

# uncomment and adjust the following line if the expected base URL of your website is something like [www.thebase.com/yourproject/]
# please do read the docs on deployment to avoid common issues: https://franklinjl.org/workflow/deploy/#deploying_your_website
# prepath = "yourproject"

# Add here files or directories that should be ignored by Franklin, otherwise
# these files might be copied and, if markdown, processed by Franklin which
# you might not want. Indicate directories by ending the name with a `/`.
# Base files such as LICENSE.md and README.md are ignored by default.
ignore = ["node_modules/"]

# RSS (the website_{title, descr, url} must be defined to get RSS)
generate_rss = true
rss_full_content = true
rss_website_title = "Dyer Geologist"
rss_website_descr = "This is Sabastien Dyer's personal website, subscribe for blog posts on geology, science, and technology"
rss_website_url   = "https://www.scdyer.com"

website_title = "Dyer Geologist"
website_descr = "This is Sabastien Dyer's personal website, subscribe for blog posts on geology, science, and technology"
website_url = "https://www.scdyer.com"

+++

<!--
Add here global latex commands to use throughout your pages.
-->
\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}

\newcommand{\figcap}[5]{
~~~
<figure style="text-align:center;">
<a href="#5">
<img src="#5" style="padding:0;width:#4%" alt="#3" title="#2"/>
</a>
<figcaption><i>#1</i></figcaption>
</figure>
~~~
}