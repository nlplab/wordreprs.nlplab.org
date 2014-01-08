---
layout: base
---

# Word Representations #

This page contains data and code related the publication ["Size (and Domain)
Matters: Evaluating Semantic Word Representations for Biomedical Text"
by Stenetorp et al. (2012)][stenetorp2012size].

[stenetorp2012size]: http://www.zora.uzh.ch/64476/11/06_Size_and_Domain_matters.pdf

## Data ##

The word representations introduced in the publication can be found
[here][word_representations].

[word_representations]: http://weaver.nlplab.org/~soyerh/data/stenetorp2012size_ner/stenetorp2012size_ner_data.tar.gz

## Code ##

The code used for the Named Entity Recognition (NER) experiments can be found
[here][ner_repo].

The code used for the Semantic Category Disambiguation (SCD) experiments can
be found [here][scd_repo].

[ner_repo]: https://github.com/ogh/wordreprs_ner
[scd_repo]: https://github.com/ninjin/contra

## Publications ##

For details please see:

    @inproceedings{stenetorp2012size,
    author      = {Stenetorp, Pontus and Soyer, Hubert and Pyysalo, Sampo
        and Ananiadou, Sophia and Chikayama, Takashi},
    title       = {Size (and Domain) Matters: Evaluating Semantic Word
        Space Representations for Biomedical Text},
    year        = {2012},
    booktitle   = {Proceedings of the 5th International Symposium on
        Semantic Mining in Biomedicine},
    }
