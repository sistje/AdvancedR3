# AdvancedR3: Learning advanced R3 with Luke and friends

This project is about learning:

-   reproducibility when coding in R studio
-   Git and GitHub
-   Collaborating in projects ¨
-   Styling your R files

# Brief description of folder and file contents

The following folders contain:

-   `data/`: A data set called lipidomics
-   `doc/`: The learning quarto document
-   `R/`: The functions and a README file

# Installing project R package dependencies

If dependencies have been managed by using
`usethis::use_package("packagename")` through the `DESCRIPTION` file,
installing dependencies is as easy as opening the `AdvancedR3.Rproj`
file and running this command in the console:

```         
# install.packages("remotes")
remotes::install_deps()
```

You'll need to have remotes installed for this to work.

# Resource

For more information on this folder and file workflow and setup, check
out the [prodigenr](https://rostools.github.io/prodigenr) online
documentation.
