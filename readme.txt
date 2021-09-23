This tests using the rmarkdown site generator method of building a website.

reference:  
https://bookdown.org/yihui/rmarkdown/rmardown-site.html
https://bookdown.org/yihui/rmarkdown-cookbook/html-output.html
https://bookdown.org/yihui/rmarkdown/interactive-documents.html#intro-widgets

Required files:

_site.yml
index.Rmd

Other requirements:
All files have to be in a single flat directory

To build, run:
rmarkdown::render_site()
or use the build tab next to the git tab on the right
