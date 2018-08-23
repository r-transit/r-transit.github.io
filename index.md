## r-transit.org

The goals of public transit align well with the goals of open source-tools for understanding it. 

Our goal is to provide support to--and highlight work by--those building public-domain tools and data in R that contribute to policy discussions around transit.  

### R Packages
- [tidytransit](https://github.com/r-transit/tidytransit) - For:
  * reading General Transit Feed Specification (GTFS) data into a list of R dataframes. 
  * analyzing the headways and frequencies at routes and stops. 
  * creating maps and performing spatial analysis on the routes and stops (using 'sf')
- [trread](https://github.com/r-transit/trread) - for reading GTFS data in R
- [r511](https://github.com/r-transit/r511) - to find current transit data in the bay area

#### Deprecated 
* [bustt](https://github.com/r-transit/bustt) - for calculating headways and transit frequency
* [gtsf](https://github.com/r-transit/gtsf) - for working with GTFS data as map data
* [transitfeedr](https://github.com/r-transit/transitfeedr) - to find current transit data around the world

### Guides
- [how-to](http://howto.r-transit.org) - analyze transit data in R
- [awesome-r-transit](https://github.com/r-transit/awesome-r-transit) - a list of awesome R transit tools

### Contributing
You can contribute by: 

- recommending work by editing [awesome-r-transit](https://github.com/r-transit/awesome-r-transit/edit/master/README.md)
- [opening a general issue](https://github.com/r-transit/r-transit.org/issues) with questions, proposals, or example work.  
- contributing to the repositories above (via [pull requests](http://oss-watch.ac.uk/resources/pullrequest), etc). 

### Acknowledgements

This organization and the tools in it take their inspiration from the [ROpenSci gtfsr](https://github.com/ropensci/gtfsr) package. We are grateful to ROpenSci and [the contributors](https://github.com/ropensci/gtfsr/graphs/contributors) to that package. 

The commit history of code contributions in gtfsr is included in all of the packages above. Our intention was to build smaller, simpler components that can be maintained, potentially more easily, by multiple people. If you’re interested in contributing or taking ownership of one of these packages, please open an issue in one of them. 

Top / featured image cc licensed BY-NC-SA 2.0 flickr [photo by cavorite](https://flic.kr/p/8HGmJr)
