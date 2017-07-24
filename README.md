# 2015-09-elections-cantonal-budgets
# 

*Since this is a multilingual project by SRGSSR, the following information is given in English.*

## Article

The data and methods in this repository are the basis of the article ["Parteibudgets: Linke sind transparenter als die Bürgerlichen"](http://www.srf.ch/news/wahlen/wahlkampf/parteibudgets-linke-sind-transparenter-als-die-buergerlichen), published September 14th, 2015. This article is also available in:

* French: [Elections et argent: plus de 20 millions déclarés et quelques gros secrets](http://www.rts.ch/info/dossiers/2015/elections-federales/7067407-elections-et-argent-plus-de-20-millions-declares-et-quelques-gros-secrets.html)

* Italian: [Una campagna elettorale da decine di milioni di franchi](http://www.swissinfo.ch/ita/elezioni-2015_una-campagna-elettorale-da-decine-di-milioni-di-franchi/41655130)

* English: [Swiss politics: Less transparency, more spending on right](http://www.swissinfo.ch/eng/business/political-spending_survey-3a-swiss-parties-on-right-are-least-transparent/41654062)


## Description

### Preprocessing and analysis

The folder `analysis` contains all preprocessing steps done in R (as RMarkdown script `main.Rmd`). The whole process and **a detailed data description** is also available [here](http://srfdata.github.io/2015-09-elections-cantonal-budgets) as HTML-file. 

### Frontend

The app was developed with [ReactJS](https://facebook.github.io/react/). All dependencies are loaded via `npm`. Building and testing can be steered via a Makefile. 

* `make` - Install `npm` dependencies and run a dev server (with [hotloading](https://github.com/gaearon/react-hot-loader)).
* `make build` - Build (minify etc.) the app
* `make test` - open up several browser windows to test the application as embedded in the SRGSSR units' websites. 

## Exclusion of liability

The published information has been collated carefully, but no guarantee is offered of its completeness, correctness or up-to-date nature. No liability is accepted for damage or loss incurred from the use of this script or the information drawn from it. This exclusion of liability also applies to third-party content that is accessible via this offer.

## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">2015-09-elections-cantonal-budgets</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/srfdata/2015-09-elections-cantonal-budgets" property="cc:attributionName" rel="cc:attributionURL">SRF Data</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

## Contact details

If you have questions please write an email to timo.grossenbacher(at)srf.ch or write us on [Twitter](https://twitter.com/srfdata)