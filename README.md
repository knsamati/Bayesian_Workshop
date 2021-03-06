## Bayesian statistics with R / Statistiques bayésiennes avec R
#### Olivier Gimenez, 2020

[![DOI](https://zenodo.org/badge/277529982.svg)](https://zenodo.org/badge/latestdoi/277529982)

### Learning objectives / Objectifs pédagogiques

* :uk: Try and demystify Bayesian statistics, and MCMC methods :fr: Essayer de démystifier les statistiques bayésiennes, et les méthodes MCMC
* :uk: Make the difference between Bayesian and Frequentist analyses :fr: Faire la différence entre analyses bayésiennes et fréquentistes
* :uk: Understand the Methods section of a paper that does Bayesian stuff :fr: Comprendre la section Méthodes d'un papier qui utilise le bayésien
* :uk: Run Bayesian analyses with `R` (in Jags) :fr: Implémenter des analyses bayésiennes avec `R` 

### Schedule / Programme

:uk: Videos are in French, but you may enable subtitles (or closed captions) by clicking on the :gear: icon in Youtube (beware though, `R` is captioned as glass for some reasons :wine_glass:) :fr: Vidéos disponibles en français

1. :uk: Bayesian inference: Motivation and simple example (video starts [here](https://youtu.be/ncOCz-HTZS4?t=4)) :fr: Inférence bayésienne : motivation et exemple simple (la vidéo commence [ici](https://youtu.be/ncOCz-HTZS4?t=4))
2. :uk: The likelihood (video starts [here](https://youtu.be/ncOCz-HTZS4?t=1907)) :fr: La vraisemblance (la vidéo commence [ici](https://youtu.be/ncOCz-HTZS4?t=1907)) 
3. :uk: A detour to explore priors (video starts [here](https://youtu.be/ncOCz-HTZS4?t=3477) and goes on [there](https://youtu.be/Aj3-LR9zcDs)) :fr: Un détour par les priors (la vidéo commence [ici](https://youtu.be/ncOCz-HTZS4?t=3477) et continue [là](https://youtu.be/Aj3-LR9zcDs))
4. :uk: Markov chains Monte Carlo methods (MCMC) (video starts [here](https://youtu.be/Aj3-LR9zcDs?t=281)) :fr: Les méthodes de Monte Carlo par chaînes de Markov (MCMC) (la vidéo commence [ici](https://youtu.be/Aj3-LR9zcDs?t=281))
5. :uk: Bayesian analyses in R with the Jags software (video starts [here](https://youtu.be/Aj3-LR9zcDs?t=3055) and goes on [there](https://youtu.be/gprytbDxcD8?t=1)) :fr: Analyses bayésiennes avec R et le logiciel Jags (la vidéo commence [ici](https://youtu.be/Aj3-LR9zcDs?t=3055) et continue [là](https://youtu.be/gprytbDxcD8?t=1))
6. :uk: Contrast scientific hypotheses with model selection (WAIC) (video starts [here](https://youtu.be/gprytbDxcD8?t=2068)) :fr: Contraster des hypothèses scientifiques avec la sélection de modèles (WAIC) (la vidéo commence [ici](https://youtu.be/gprytbDxcD8?t=2068))
7. :uk: Heterogeneity and multilevel models (aka mixed models) (video starts [here](https://youtu.be/gprytbDxcD8?t=3128) and goes on [there](https://youtu.be/EaxQGJVJmIw?t=1)) :fr: Hétérogénéité et modèles multiniveaux ou mixtes (la vidéo commence [ici](https://youtu.be/gprytbDxcD8?t=3128) et continue [là](https://youtu.be/EaxQGJVJmIw?t=1)) 

### Slides, videos, code and data / Diapos, vidéos, code et données

* :uk: Slides available [here](https://doi.org/10.6084/m9.figshare.12656894.v2) :fr: Diapos disponible [ici](https://doi.org/10.6084/m9.figshare.12656894.v2)
* :uk: Videos available in French via Youtube (you may enable subtitles or closed captions by clicking on the gear icon; `R` is captioned as glass for some reasons) :fr: Vidéos disponibles en français
   + slides 1-80, watch [here](https://youtu.be/ncOCz-HTZS4?t=1) / diapos 1-80, regardez [ici](https://youtu.be/ncOCz-HTZS4?t=1)
   + slides 81-131, watch [here](https://youtu.be/Aj3-LR9zcDs?t=1) / diapos 81-131, regardez [ici](https://youtu.be/Aj3-LR9zcDs?t=1)
   + slides 132-171, watch [here](https://youtu.be/gprytbDxcD8?t=1) / diapos 132-171, regardez [ici](https://youtu.be/gprytbDxcD8?t=1) 
   + slides 172-end, watch [here](https://youtu.be/EaxQGJVJmIw?t=1) / diapos 172-fin, regardez [ici](https://youtu.be/EaxQGJVJmIw?t=1) 
* :uk: All material prepared in `R` / Matériel préparé avec `R`
   + `R` code available [here](https://raw.githubusercontent.com/oliviergimenez/Bayesian_Workshop/master/BayesianStatistics_OGimenez.R) / code `R` disponible  [ici](https://raw.githubusercontent.com/oliviergimenez/Bayesian_Workshop/master/BayesianStatistics_OGimenez.R)
   + `R Markdown` used to write reproducible material (source code [here](https://raw.githubusercontent.com/oliviergimenez/Bayesian_Workshop/master/BayesianStatistics_OGimenez.Rmd)) :fr: `R Markdown` utilisé pour écrire les diapos (code [ici](https://raw.githubusercontent.com/oliviergimenez/Bayesian_Workshop/master/BayesianStatistics_OGimenez.Rmd)).
* :uk: Material available via Github [there](https://github.com/oliviergimenez/Bayesian_Workshop) :fr: Matériel disponible via Github [là](https://github.com/oliviergimenez/Bayesian_Workshop)

### Credits / Crédits

* :uk: Many slides are from [a workshop we used to run a loooong time ago](https://www.maths.ed.ac.uk/~rking33/Book-website/index.html) with Ruth King, Byron Morgan and Steve Brooks. I also re-used or adapted slides by [Richard McElreath](https://github.com/rmcelreath/statrethinking_winter2019) (16-20, 90-91, 166, 186), [Kerrie Mengersen](https://staff.qut.edu.au/staff/k.mengersen) (16-20, 81), [Francisco Rodriguez Sanchez](https://frodriguezsanchez.net/) (79-80; from the Stan manual), [Jim Albert and Jingchen Hu](https://bayesball.github.io/BOOK/probability-a-measurement-of-uncertainty.html) (93-99), [Tristan Marh](https://www.tjmahr.com/) (22), [Jason Matthiopoulos](https://www.gla.ac.uk/researchinstitutes/bahcm/staff/jasonmatthiopoulos/) (31-39, 196), a paper by [Michael McCarthy and Pip Masters](https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/j.1365-2664.2005.01101.x) (71-73), [Andrés Lopez-Sepulcre](https://www.lopez-sepulcre.com/) (126) and [John Kruschke' book cover](https://sites.google.com/site/doingbayesiandataanalysis/) (61) :fr: Plusieurs diapos sont tirées d'[un workshop que nous organisions il y a bien longtemps](https://www.maths.ed.ac.uk/~rking33/Book-website/index.html) avec Ruth King, Byron Morgan et Steve Brooks. J'ai aussi utilisé et adapté des diapos de [Richard McElreath](https://github.com/rmcelreath/statrethinking_winter2019) (16-20, 90-91, 166, 186), [Kerrie Mengersen](https://staff.qut.edu.au/staff/k.mengersen) (16-20, 81), [Francisco Rodriguez Sanchez](https://frodriguezsanchez.net/) (79-80; from the Stan manual), [Jim Albert and Jingchen Hu](https://bayesball.github.io/BOOK/probability-a-measurement-of-uncertainty.html) (93-99), [Tristan Marh](https://www.tjmahr.com/) (22), [Jason Matthiopoulos](https://www.gla.ac.uk/researchinstitutes/bahcm/staff/jasonmatthiopoulos/) (31-39, 196), un papier de [Michael McCarthy et Pip Masters](https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/j.1365-2664.2005.01101.x) (71-73), [Andrés Lopez-Sepulcre](https://www.lopez-sepulcre.com/) (126) et [la couverture du livre de John Kruschke](https://sites.google.com/site/doingbayesiandataanalysis/) (61). 

* :uk: The sources for the images are: [James Kulich](https://www.elmhurst.edu/blog/thomas-bayes/) for slide 13, Matt Buck for slide 21, [xkcd](https://xkcd.com/1132/) for slide 29 and Mike West for slide 194 :fr: Les sources des images sont : [James Kulich](https://www.elmhurst.edu/blog/thomas-bayes/) pour la diapo 13, Matt Buck pour la diapo 21, [xkcd](https://xkcd.com/1132/) pour la diapo 29 et Mike West pour la diapo 194

### How to use this repo? / Comment utiliser ce dossier?

* :uk: Click on the `Code` green button at the top right of the page to create a copy of the repo within your own GitHub account (clone) :fr: Cliquez sur le bouton vert `Code` en haut à droite et créer une copie du doossier dans votre compte GitHub (clone)
* :uk: Alternately, click on the same green button and choose `Download ZIP` to download the repo to your computer :fr: Sinon, cliquez sur le même bouton vert et choisissez `Download ZIP` pour télécharger le dossier compressé sur votre ordinateur

### Requirements / Logiciels à installer

* :uk: You need to have `R` or `RStudio` installed :fr: Il vous faut `R` ou `RStudio`
* :uk: Download `Jags` from [sourceforge](http://sourceforge.net/projects/mcmc-jags/files/) and install it :fr: Téléchargez `Jags` depuis [sourceforge](http://sourceforge.net/projects/mcmc-jags/files/) et installez-le.
* :uk: Install package `R2jags` from `R` or `RStudio` :fr: Installez le package `R2jags` depuis `R` ou `RStudio`

### Problem / Problème

:uk: If you spot a typo or an error, find a bug, or have trouble running the code, please [file an issue](https://github.com/oliviergimenez/Bayesian_Workshop/issues) or [get back to me](mailto:olivier.gimenez@cefe.cnrs.fr) :fr: Si vous voyez une faute ou une erreur, ou un bug, n'hésitez pas à [remplir un formulaire](https://github.com/oliviergimenez/Bayesian_Workshop/issues) ou [me contacter](mailto:olivier.gimenez@cefe.cnrs.fr)

### Licence / License

:uk: This work is licensed under a
[Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/) :fr: Ce travail est sous license [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/)

### To-do list

* Short term   
   + Mention that besides `Jags`, `Stan` and `Nimble`, there are other software options to fit models in the Bayesian framework that do not need coding. Check out the [CRAN Task View: Bayesian Inference](https://cran.r-project.org/web/views/Bayesian.html).
   + Mention the availability of free Bayesian books: [here](https://www.bookdown.org/home/tags/bayesian/) and Gelman BDA [there](http://www.stat.columbia.edu/~gelman/book/).  
   + Add a plot with several lines from posterior distribution of regression parameters to a plot of mean response function of a covariate; then get the credible interval on the prediction. 
   + R 4.0 no longer converts automatically chains of characters in factors when reading file; while it is a good thing, this causes a problem in the plant example on GLMM with older R versions; just need to add an extra step for converting the Sp column into a factor (Sp <- as.factor(Sp)).
   + Say more on prior predictive checks. 
   + Say something about confidence, credible and HPD intervals.
   + Add another Metropolis example, with adaptation, with the beta-binomial example, and discuss several levels of acceptance. 
   + Add a section on posterior predictive checks, to comply with the 3 steps of a Bayesian analysis as defined by Gelman (set up a probabilistic model, inference and model checking; iterate to improve model).
   + Do all plots with `ggplot2`; add [short introduction to the `Tidyverse`](https://github.com/oliviergimenez/intro_tidyverse).
   + ~~Add a short section on sequential analysis (today prior is yesterday posterior).~~
   + ~~Add an example with Poisson GLM(M) example.~~
   + In the GLMM section with the plant example, decide to go for number of seeds or log(number of seeds)
   + Explain the WAIC in more details
   + Properly introduce GLMs


* Mid term   

   + Add a section on LOO, and discuss complementarity with WAIC.
   + Add a section on models with varying slopes. Can we use the [LKJ prior](https://www.sciencedirect.com/science/article/pii/S0047259X09000876) in `Jags` and `Nimble` ?
   + Write a short introduction to `Nimble` (resp. `Stan`) and provide both the `Jags` and `Nimble` (resp. `Stan`) codes. Translating `Jags` code in `Nimble` is [easy](https://r-nimble.org/quick-guide-for-converting-from-jags-or-bugs-to-nimble). For now, check out [training materials](https://github.com/nimble-training) and [examples](https://r-nimble.org/examples).
   + Add a section on population ecology (occupancy models, capture-recapture models). And/or something on hierarchical models, models with hidden variables. Make use of [nimbleEcology](https://cran.r-project.org/web/packages/nimbleEcology/vignettes/Introduction_to_nimbleEcology.html).
   + Add a section on [penalized splines](https://www.cambridge.org/core/books/semiparametric-regression/02FC9A9435232CA67532B4D31874412C) (possibly using package `jagam`) and [spatial analyses](https://r-nimble.org/html_manual/cha-spatial.html).

* Long term

   + Write a book (whaaaaat?!)
