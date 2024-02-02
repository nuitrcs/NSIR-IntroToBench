# NSIR-IntroToBench

Taught by John Lee Winter Quarter of 2024 Northwestern University's Research Computing and Data Services. The workshop was taught as part of the winter 2024 [Next Steps in R series](https://github.com/nuitrcs/Next-steps-in-R).


# Getting Started
* Download the materials to your machine by clicking on the green "Code" button on the top right and selecting "Download ZIP".
* Unzip the downloaded folder, and double-click on the .RProj file to open up the R Project in RStudio.
* Open `nsir-bench.qmd` and work through the materials.


# Concepts

* Benchmark
* Timing your code with base R function `system.time()`
* Using `mark` and `press` from the `{bench}` package
* Comparing performance across different approaches of a problem

# Components

* README.md markdown file outlining the repository
* .Rproj folder maintaining an R Project for this directory
* `nsir-bench.qmd` Quarto document with the workshop contents

# Required Installs
* R and RStudio
* Packages: `bench`, `ggplot2`, `tidyr`, `ggbeeswarm`, `ggridges`

```
install.packages("bench")
install.packages("ggplot2")
install.packages("tidyr")
install.packages("ggbeeswarm")
install.packages("ggridges")
```
