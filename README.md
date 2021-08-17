# LinkedIn Analysis

This analysis was completed for my own knowledge of my LinkedIn network. The 
data is fairly sparse, but still interesting nonetheless.


# Create Your Own Analysis

## Prerequisites 

### Environment

This analysis assumes you have [R](https://www.r-project.org) & 
[RStudio](https://www.rstudio.com) installed. It also assumes that you have a 
number of R Packages installed:

```{r}
install.packages(c("rmarkdown", "dplyr", "ggplot2", "kableExtra", "knitr",
                   "scales"))
```

### Data

This analysis also assumes that you've downloaded your connection data from 
LinkedIn (instructions on that can be found 
[here](https://www.linkedin.com/help/linkedin/answer/66844/export-connections-from-linkedin?lang=en)) and placed the unzipped data into the `data/raw` directory. 
That file should be named `Connections.csv`.

## Analysis

Once you have your environment set up and the data downloaded and placed in the 
correct directory, open the file `final_analysis.Rmd` in RStudio and click 
knit. This will generate an HTML file with your information!