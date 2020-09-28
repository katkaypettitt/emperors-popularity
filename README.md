# Roman Emperors and Online Popularity

> Which Roman emperors have more online popularity on a global scale and does this vary according to when and how long an emperor reigns? Two extensive datasets documenting Roman emperors and a metric called the Historical Popularity Index (HPI) are used to explore this question. 

## Table of contents

* [General info](#general-info)
* [Technologies](#technologies)
* [Features](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info

This study combines two datasets to explore the relationship between modern online global popularity and ancient Roman emperors. The resulting figure (saved in the repository as ```emperors-popularity.pdf```) illustrates there is a general trend for early reigning emperors (colour bar and markers), as well as emperors whose reign lasted longer (x-axis), to be more well-known (y-axis). This is undoubtedly related to the plethora of primary sources in the early and middle empire and the coverage they have received in popular media (i.e., films, TV series, video games, and books). 

The data on Roman emperors was extracted and modified by a Roman emperor dataset on Kaggle. The second dataset, Pantheon 1.0, was published in 2016 and documents the online popularity of over 11,000 historical characters. It has been used in the entertainment and education industries, including academic publications. This dataset is particularly interesting since it takes into consideration an entry’s global popularity in multiple languages versus over-relying on English language based hits. For more information on the Pantheon 1.0 dataset and the methdology used, [see the Pantheon website.](https://pantheon.world/)

50/68 of the emperors are covered in Pantheon 1.0, with the majority of those missing being from the late Roman Empire. As a former Classicist, I can also attest to the relative obscurity of the emperors without an entry. Additionally, one Nerva-Antonine emperor was excluded from the figure as an outlier. 

The utilised data files are detailed below:

* ['Roman emperors from 26 BC to 385 AD'](https://www.kaggle.com/lberder/roman-emperors-from-26-bc-to-395-ad) [Kaggle version: October 2017]: Contains information about each Roman emperor. Saved as ```roman-emperors.zip```. Also available here: [Nation, Z. (2016). emperor [GitHub repository]](https://github.com/zonination/emperors).
* ['Pantheon 1.0 dataset'](https://pantheon.world/data/datasets): Contains entries of over 11,000 historical figures with Wikpedia biographies in multiple languages. Saved as ```pantheon.tsv.bz2```. Also available here: ['Pantheon Project: Historical Popularity Index'](https://www.kaggle.com/mit/pantheon-project).
  (Yu, A. Z., et al. (2016). Pantheon 1.0, a manually verified dataset of globally famous biographies. *Scientific Data* 2:150075. doi: 10.1038/sdata.2015.75)

## Technologies

Python 3.7.6

## Status

Project is _finished_.

## Inspiration

This project is partly inspired by my Master's dissertation, completed back in 2012, which explored how later (vs contemporary) primary sources depicted the emperor Caligula in a more negative light, thus influencing modern day perceptions.

## Contact

Created by [@katrinaalaimo](https://www.katrinaalaimo.com/) — feel free to contact me!