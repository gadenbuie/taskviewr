This [Shiny](https://shiny.rstudio.com/) application was created by Mikhail Popov (@bearloga on [Twitter](https://twitter.com/bearloga) and [GitHub](https://github.com/bearloga)) to quickly browse packages and their licenses using a snapshot of task views retrieved on
2017-02-07.

R packages used in the creation of this app include: [ctv](https://cran.r-project.org/package=ctv) (for getting the list of packages in each task view), [purrr](https://cran.r-project.org/package=purrr) + [dplyr](https://cran.r-project.org/package=dplyr) (for manipulating the acquired data), [crandb](https://github.com/metacran/crandb) for obtaining licensing and other details for each package, and [shiny](https://cran.r-project.org/package=shiny) + [shinythemes](https://cran.r-project.org/package=shinythemes) + [DT](https://cran.r-project.org/package=DT) for surfacing all of that data (which is [available as a CSV](https://github.com/bearloga/taskviewr/raw/master/www/packages.csv)). The source code is [available on GitHub](https://github.com/bearloga/taskviewr).

This project is **not** affiliated with [The Comprehensive R Archive Network](https://cran.r-project.org/) or [The R Foundation](https://www.r-project.org/).
