# make-wb-20mph

`rstats/blogdown` site about traffic and making wb in nottingham a 20mph zone.

- this repo is the rendered HTML version of the blogdown site, so we can use github pages for hosting 

- I use `RStudio` and `blogdown` to build the webpage and then push the finished `public` directory to this repo, which has `github-pages` hosting enabled.  need to making sure to disable `jekyll` conversion by including a `.nojekyll` file as a semaphore.

- the code for creating some of the visualisations, maps, etc. is kept in a separate repo [schluppeck/make-wb-20mph](https://github.com/schluppeck/make-wb-20mph-code). The `Rmd` files contains the chunks of `R` needed to download data, aggregate, compute, render, etc. if you want to have a look yourself.

- I will add comments / references as I go along

-ds

