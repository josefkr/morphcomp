Last edit: Sun Sep  3 2017
Author: Josef Ruppenhofer

# Overview

The files in this directory constitute the data release
accompanying the publication at RANLP 2017 of

"Evaluating the morphological compositionality of polarity"

by Josef Ruppenhofer, Petra Steiner and Michael Wiegand.

# License

The polarity annotations and morphological parses that were created by the above authors for this work are licensed under the Creative Commons Attribution-ShareAlike 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by-sa/4.0/ or send a letter to Creative Commons, 444 Castro Street, Suite 900, Mountain View, California, 94041, USA.

# Data sets

There are three different data sets that are used in the experiments of the above mentioned paper:

- The main data set which derives from the combination of PolArt and CELEX.
It combines (i)  words from PolArt for which a morphological parse existed in CELEX with (ii) additional words taken from CELEX for which we added polarity annotations. The new words from CELEX were added so as to have a more sizable  share of the neutral class in the overall data set.
The main data set is split up into a train/test part (8400 items) and a dev(elopment) part (900) items.

To reconstitute this dataset you need to obtain PolArt** (free) and CELEX (licensed by LDC: https://catalog.ldc.upenn.edu/ldc96l14). Our own license above does not cover these additional resources.

** We downloaded PolArt a while ago from
http://kitt.cl.uzh.ch/kitt/polart/

A successor/update is now available here:
http://bics.sentimental.li/files/8614/2462/8150/german.lex


- To go along with the polarity information for simple and complex words from PolArt, we also created polarity annotations for affixes.

- The Wortwarte (wortwarte.de) data set contains a random sample of items identified as neologisms by the Wortwarte project. We created polarity annotations and morphological parses for these items.

-  The third data set are compounds taken from the German version of Wiktionary. These items were also annotated for polarity by us and we provided morphological parses for these items if they were not already covered by CELEX.

If you would like to also use the psycholinguistic features referenced in the paper, please obtain them from the website of Sabine Schulte im Walde: http://www.schulteimwalde.de/resources/affective-norms.html

To consult the accompanying publication, look for:

@inproceedings{koper2016automatically,
  title={Automatically generated affective norms of abstractness, arousal, imageability and valence for 350000 german lemmas},
  author={Maximilian K{\"o}per  and Sabine {Schulte im Walde}},
  booktitle={Proceedings of the 10th International Conference on Language Resources and Evaluation},
  pages={2595--2598},
  year={2016}
}

# Citing this work

Please cite the above mentioned paper

@inproceedings{rsw2017,
       booktitle = {Proceedings of RANLP 2017},
           month = {September},
           title = {Evaluating the morphological compositionality of polarity},
          author = {Josef Ruppenhofer and Petra Steiner and Michael Wiegand,
            year = {2017},
}


and please also acknowledge PolArt and CELEX if you use them:

@inproceedings{zora19792,
       booktitle = {17th Nordic Conference on Computational Linguistics (NODALIDA 2009)},
           month = {May},
           title = {PolArt: a robust tool for sentiment analysis},
          author = {Manfred Klenner  and Angela Fahrni and Stefanos Petrakis},
            year = {2009},
             url = {http://dx.doi.org/10.5167/uzh-19792}
}

@misc{Baayen+93,
    address = {Philadelphia, PA},
    author = {{R. Harald} Baayen  and Richard Piepenbrock and Léon Gulikers},
    publisher = {Linguistic Data Consortium},
    title = {CELEX2 LDC96L14},
    year = {1995}
}



# Files

* README.md - this file
* affix_polarities.txt - polarity annotations for German affixes
* dev_lemma_polarity.txt - polarity annotations for the lemmas of the dev(elopment) set
* train_test_lemma_polarity.txt - polarity annotations for the lemmas of the train/test set
* wiktionary_lemma_parse.txt - morphological parses for the wiktionary lemmas
* wiktionary_lemma_polarity.txt - polarity annotations for the lemmas taken from Wiktionary
* wortwarte_lemma_parse.txt - morphological parses for the Worwarte lemmas
* wortwarte_lemma_polarity.txt-  polarity annotations for the lemmas taken from Wortwarte
