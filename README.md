# Road2R

A curated list of amazingly awesome R libraries, resources and package collection.  

!['R logo'](Rlogonew.png)

## Contributing Information
Please see [author's details](https://github.com/Ronlee12355) and author's [personal website](http://www.ronleecww.cn)!   
Collaboration and pull requests are always welcomed!   

## Workflow for Data Science
!['workflow of data science'](data-science.png)

## Workflow of Text Mining
!['workflow of text mining'](tidyflow.png)

## Table of Contents
- [Road2R](#Road2R)
	- [Package collection](#data-manipulation)
		- [Data manipulation](#data-manipulation)
		- [Visualization](#visualization)
		- [Import data](#import-data)
		- [Network graph](#network-graph)
		- [Interactive Graphics](#interactive-graphics)
		- [Word cloud](#word-cloud)
		- [Text mining](#text-mining)
		- [Machine learning](#machine-learning)
		- [Time series](#time-series)
		- [Markdown](#markdown)
		- [Development in R](#development-in-r)
	- [Online blogs](#online-blogs)
	- [Learning materials](#learning-materials)
	
### Data manipulation
*Packages that enable you to manipulate data*

* [dplyr](https://github.com/hadley/dplyr) - a grammar of data manipulation.
* [tibble](https://github.com/hadley/tibble) - efficient display structure for tabular data.
* [dbplyr](https://github.com/tidyverse/dbplyr) - A 'dplyr' Back End for Databases.
* [plyr](https://github.com/hadley/plyr) - the split-apply-combine paradigm for R.
* [tidyr](https://github.com/tidyverse/tidyr) - Easily Tidy Data with 'spread()' and 'gather()' Functions.
* [jsonlite](https://arxiv.org/abs/1403.2805) - A Robust, High Performance JSON Parser and Generator for R.
* [stringr](https://github.com/tidyverse/stringr) - Simple, Consistent Wrappers for Common String Operations.
* [stringi](http://www.gagolewski.com/software/stringi/) - Character String Processing Facilities.
* [data.table](http://r-datatable.com) - Extension of "data.frame".
* [magrittr](https://github.com/smbache/magrittr) - A Forward-Pipe Operator for R.
* [reshape2](https://github.com/hadley/reshape) - Flexibly Reshape Data: A Reboot of the Reshape Package.
* [forcats](https://github.com/tidyverse/forcats) - Tools for Working with Categorical Variables (Factors).
* [broom](http://github.com/tidyverse/broom) - Convert Statistical Analysis Objects into Tidy Data Frames.
* [Matrix](http://Matrix.R-forge.R-project.org/) - Sparse and Dense Matrix Classes and Methods.
* [lubridate](https://github.com/tidyverse/lubridate) - Make Dealing with Dates a Little Easier.
* [xts](http://r-forge.r-project.org/projects/xts) - tools for time series based data.
* [hashmap](https://github.com/nathan-russell/hashmap) - The Faster Hash Map.
* [rlist](https://github.com/rekun-ken/rlist) - A Toolbox for Non-Tabular Data Manipulation.
* [yaml](https://github.com/viking/r-yaml/) - Methods to Convert R Data to YAML and Back.
* [xml2](https://github.com/hadley/xml2/) - Parse XML.
* [lobstr](https://lobstr.r-lib.org) - lobstr provides tools in the same vein as str(), which allow you to dig into the detail of an object.


### Visualization
*Packages that enable you to plot*

* [ggplot2](https://github.com/tidyverse/ggplot2) - Create Elegant Data Visualisations Using the Grammar of Graphics.
* [gganinate](http://github.com/thomasp85/gganimate) - A Grammar of Animated Graphics.
* [ggedit](https://github.com/metrumresearchgroup/ggedit) - Interactive 'ggplot2' Layer and Theme Aesthetic Editor.
* [ggfittext](https://github.com/wilkox/ggfittext) - Fit Text Inside a Box in 'ggplot2'.
* [ggforce](https://cran.r-project.org/package=ggforce) - Accelerating 'ggplot2'.
* [gggenes](https://github.com/wilkox/gggenes) - Draw Arrow Maps in 'ggplot2'. 
* [ggnetwork](https://cran.r-project.org/package=ggnetwork) - Geometrics to Plot Networks with ''ggplot2''. 
* [ggmap](https://github.com/dkahle/ggmap) - Spatial Visualization with ''ggplot2''. 
* [ggpubr](http:/www.sthda.com/english/rpkgs/ggpubr) - ''ggplot2'' Based Publication Ready Plots. 
* [ggrepel](http://github.com/slowkow/ggrepel) - Automatically Position Non-Overlapping Text Labels with 'ggplot2'.
* [ggridge](https://github.com/clauswilke/ggridges) - Ridgeline Plots in 'ggplot2'.
* [ggsci](https://github.com/road2stat/ggsci) - Scientific Journal and Sci-Fi Themed Color palettes for 'ggplot2'.
* [ggsignif](https://github.com/const-ae/ggsignif) - Significance Brackets for 'ggplot2'.
* [ggthemes](http://github.com/jrnold/ggthemes) - Extra Themes, Scales and Geoms for 'ggplot2'.
* [ggvis](http://ggvis.rstudio.com) - Interactive Grammar of Graphics.
* [cowplot](https://github.com/wilkelab/cowplot) - Streamlined Plot Theme and Plot Annotations for 'ggplot2'.
* [treemapify](https://github.com/wilkox/treemapify) - Draw Treemaps in 'ggplot2'.
* [ggalluvial](http://corybrunson.github.io/ggalluvial/) - Alluvial Diagrams in 'ggplot2'.
* [GGally](https://github.com/ggobi/ggally) - Extension to 'ggplot2'.
* [alluvial](https://github.com/mbojan/alluvial) - Alluvial Diagrams.
* [corrplot](https://github.com/taiyun/corrplot) - Visualization of a Correlation Matrix.
* [arulesViz](https://github.com/mhahsler/arulesViz) - Visualizing Association Rules and Frequent Itemsets.
* [gplots](https://cran.r-project.org/package=gplots) - Various R Programming Tools for Plotting Data.
* [rpart.plot](http://www.milbo.org/rpart-plot) - Plot 'rpart' Models: An Enhanced Version of 'plot.rpart'.
* [survival](https://github.com/therneau/survival/) - Survival Analysis. 
* [pheatmap](https://cran.r-project.org/package=pheatmap) - Pretty Heatmap.
* [ROCR](http://rocr.bioinf.mpi-sb.mpg.de) - Visualization the Performance of Scoring Classifiers.
* [pROC](http://expasy.org/tools/pROC/) - Display and Analyze ROC Curves.
* [ggstance](https://github.com/lionel-/ggstance) - Horizontal versions of common plots.
* [ggExtra](https://github.com/daattali/ggExtra) - Marginal histograms for a plot.


### Import Data
*Packages that enable you to import, load and save data*

* [readr](https://github.com/tidyverse/readr) - Read Rectangular Text Data.
* [openxlsx](https://github.com/awalker89/openxlsx) - Read, Write and Edit XLSX Files
* [readxl](https://github.com/tidyverse/readxl) - Read Excel Files.
* [clipr](https://github.com/mdlincoln/clipr) - Read and Write from the System Clipboard.
* [data.table](http://r-datatable.com) - Extension of "data.frame".
* [feather](https://github.com/wesm/feather) - R Bindings to the Feather 'API'.
* [haven](https://github.com/tidyverse/haven) - Import and Export 'SPSS', 'Stata' and 'SAS' Files.
* [httr](https://github.com/r-lib/httr) - Tools for Working with URLs and HTTP.
* [rvest](https://github.com/hadley/rvest) - Easily Harvest (Scrape) Web Pages.
* [DBI](http://r-dbi.github.io/DBI) - R Database Interface
* [RMySQL](https://github.com/rstats-db/RMySQL) - MySQL driver for DBI
* [RPostgres](https://github.com/rstats-db/RPostgres) - Postgres driver for DBI
* [RSQLite](https://github.com/rstats-db/RSQLite) - SQlite driver for DBI
* [git2r](https://github.com/ropensci/git2r) - Provides Access to Git Repositories.
* [RCurl](http://www.omegahat.net/RCurl) - General Network (HTTP/FTP/...) Client Interface for R.

### Network graph
*packages that enable you to visualize network*

* [igraph](http://igraph.org) - Network Analysis and Visualization.
* [ggnetwork](https://cran.r-project.org/package=ggnetwork) - Geometrics to Plot Networks with ''ggplot2''.  
* [network3D](https://CRAN.R-project.org/package=networkD3) - D3 JavaScript Network Graphs from R.
* [network](http://statnet.org/) - Classes for Relational Data.
* [sna](http://www.statnet.org) - Tools for Social Network Analysis.
* [snow](https://CRAN.R-project.org/package=snow) - Simple Network of Workstations.
* [visNetwork](http://datastorm-open.github.io/visNetwork/) - Network Visualization using 'vis.js' Library.


### Interactive Graphics
*packages that enable you to make interactive graphics*

* [htmlwidgets](http://www.htmlwidgets.org/) - framework for creating JavaScript widgets with R.
* [networkD3](http://christophergandrud.github.io/networkD3/) - Interative d3 network graphs.
* [d3heatmap](https://github.com/rstudio/d3heatmap) - Interactive d3 heatmaps.
* [DT](http://rstudio.github.io/DT/) - Interactive tables.
* REmap - Create html maps by Echarts.
* [echarts4r](https://github.com/JohnCoene/echarts) - EChart htmlwidget.
* [leaflet](http://rstudio.github.io/leaflet/) - Interactive maps.
* [plotly](https://plot.ly/r/) - Interactive plots.
* [Highcharter](http://jkunst.com/highcharter/) - Interactive Highcharts plots.
* [visNetwork](http://dataknowledge.github.io/visNetwork) - Interactive network graphs.


### Word cloud
*packages that enable you to draw word cloud*

* [wordcloud](http://research.cens.ucla.edu/) - Word Clouds.
* [wordcloud2](https://github.com/lchiffon/wordcloud2) - Create Word Cloud by 'htmlwidget'.


### Text mining
*packages that enable you to do text mining*

* [tidytext](http://github.com/juliasilge/tidytext) - Text Mining using 'dplyr', 'ggplot2', and Other Tidy Tools.
* [widyr](http://github.com/dgrtwo/widyr) - Widen, Process, then Re-Tidy Data.
* [tm](http://tm.r-forge.r-project.org/) - Text Mining Package.
* [NLP](https://cran.r-project.org/package=NLP) - Natural Language Processing Infrastructure.
* [janeaustenr](https://cran.r-project.org/package=janeaustenr) - Jane Austen's Complete Novels.
 

### Machine learning
*packages that enable you to deploy machine learning algorithms*

* [caret](https://github.com/topepo/caret/) - Classification and Regression Training.
* [xgboost](https://github.com/dmlc/xgboost) - Extreme Gradient Boosting.
* [glmnet](http://www.jstatsoft.org/v33/i01/.) - Lasso and Elastic-Net Regularized Generalized Linear Models.
* [e1071](https://cran.r-project.org/package=e1071) - Misc Functions of the Department of Statistics, ProbabilityTheory Group (Formerly: E1071), TU Wien.
* [arules](https://github.com/mhahsler/arules) - Mining Association Rules and Frequent Itemsets.
* [car](https://CRAN.R-project.org/package=car) - Companion to Applied Regression.
* [igraph](http://igraph.org) - PageRank algotirhm.
* [kernlab](https://cran.r-project.org/package=kernlab) - Kernel-Based Machine Learning Lab.
* [modelr](https://github.com/hadley/modelr) - Modelling Functions that Work with the Pipe.
* [gbm](https://github.com/gbm-developers/gbm) - gradient boosted regression models.
* [nlme](https://cran.r-project.org/package=nlme) - Linear and Nonlinear Mixed Effects Models.
* [randomForest](https://www.stat.berkeley.edu/~breiman/RandomForests/) - Breiman and Cutler's Random Forests for Classification and Regression.
* [rpart](https://cran.r-project.org/package=rpart) - Recursive Partitioning and Regression Trees.
* [boot](https://cran.r-project.org/package=boot) - Bootstrap Functions (Originally by Angelo Canty for S).
* [gbm](https://github.com/gbm-developers/gbm) - gradient boosted regression models.
* [nnet](http://www.stats.ox.ac.uk/pub/MASS4/) - Feed-Forward Neural Networks and Multinomial Log-Linear Models.
* [neuralnet](https://github.com/bips-hb/neuralnet) - Training of Neural Networks.
* [h2o](http://www.h2o.ai/) - parallel distributed machine learning algorithms.
* [mlr](https://github.com/mlr-org/mlr) - Machine Learning in R.
* [ggpomological](https://github.com/gadenbuie/ggpomological) - Pomological Colors.


### Time series
*packages that enable you to play with time*

* [xts](https://github.com/joshuaulrich/xts) - eXtensible Time Series.
* [forecast](https://github.com/robjhyndman/forecast) - Forecasting Functions for Time Series and Linear Models.
* [zoo](http://zoo.R-Forge.R-project.org/) - S3 Infrastructure for Regular and Irregular Time Series (Z's Ordered Observations).


### Markdown
*packages that enable you to write markdwon in R*

* [rmarkdown](https://github.com/rstudio/rmarkdown) - Dynamic Documents for R.
* [rsconnect](https://cran.r-project.org/package=rsconnect) - Deployment Interface for R Markdown Documents and Shiny Applications.
* [knit](https://yihui.name/knitr/) - A General-Purpose Package for Dynamic Report Generation in R.

### Development in R
*packages that enable you to develop your own project*

* [devtools](https://github.com/r-lib/devtools) - Tools to Make Developing R Packages Easier.
* [Rcpp](https://github.com/RcppCore/Rcpp) - Seamless R and C++ Integration.
* [testthat](https://github.com/r-lib/testthat) - Unit Testing for R.
* [roxygen2](https://github.com/klutometis/roxygen) - In-Line Documentation for R.
* [bindrcpp](https://github.com/krlmlr/bindrcpp) - An 'Rcpp' Interface to Active Bindings.
* [RStudio Desktop IDE](https://www.rstudio.com/products/rstudio/#Desktop) - IDE.
* [RStudio Server Open Source](https://www.rstudio.com/products/rstudio/#Server) - server IDE.
* [Anaconda](https://www.anaconda.com) - The World's Most Popular Python/R Data Science Platform.
* [Visual Studio Code](https://code.visualstudio.com) - Open source code editor.


### Online blogs
*Online blogs.*

* [RPubs](http://www.rpubs.com) - Easy web publishing from R.
* [Shinyapps](https://www.shinyapps.io/) - Share your Shiny Applications Online.
* [R-bloggers](https://www.r-bloggers.com) - R news and tutorials contributed by (750) R bloggers.
* [RWeekly](https://rweekly.org) - Weekly Updates from the Entire R Community.
* [RDocumentation](https://www.rdocumentation.org) - Search all 16,944 CRAN, Bioconductor and GitHub packages.
* [Rstudio Community](https://community.rstudio.com) - The Rstudio Community.


### Learning materials
*Online learning materials*  

* [Writing R extension](https://cran.r-project.org/doc/manuals/r-release/R-exts.pdf) - The online pdf of telling you how to write your own packages.
* [R packages](http://r-pkgs.had.co.nz) - This is the book site for “R packages”. It was published with O’Reilly in April 2015.
* [R for Data Science](https://r4ds.had.co.nz) - This is the website for “R for Data Science”.
* [Text Mining with R - A Tidy Approach](https://www.tidytextmining.com) - This is the website for Text Mining with R.
* [R Start Here](https://github.com/rstudio/RStartHere) - A guide to some of the most useful R Packages that we know about.
* [ggplot2 Doc](https://ggplot2.tidyverse.org/reference/) - Reference of ggplot2.
* [Plotly for R](https://plotly-r.com/index.html) - plotly for R.
* [Efficient R programming](https://csgillespie.github.io/efficientR/) - Efficient R programming by Colin Gillespie and Robin Lovelace.
* [Advanced R](https://adv-r.hadley.nz/) - Advanced R.
* [bookdown: Authoring Books and Technical ](https://bookdown.org/yihui/bookdown/) - Documents with R Markdown.
* [Geocomputation with R](https://geocompr.robinlovelace.net/) - Geocomputation with R.
* [knitr](https://yihui.name/knitr/) - knitr: elegant, flexible, and fast dynamic report generation with R.
* [Machine Learning with TensorFlow(R version)](https://github.com/haven-jeon/TensorFlow-Book-R) - This repository is for practicing R tensorflow modeling exercises.
* [R的极客理想-高级开发篇](https://github.com/bsspirit/book-r2) - R的极客理想-高级开发篇.
* [swirl](https://github.com/swirldev/swirl) - swirl is a platform for learning (and teaching) statistics and R simultaneously and interactively.
