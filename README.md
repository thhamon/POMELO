# POMELO
### POMELO Corpus

## 639 Medline abstracts annotated with Food-Drug Interactions

Version: 1.0
Creation Date: March 24, 2021
Realease Date: March 24, 2021

Authors:

Thierry Hamon, hamon@limsi.fr (corresponding author),
Vincent Tabanou,
Fleur Mougin,
Natalia Grabar,
Frantz Thiessard

## 1. Corpus Description

POMELO is a corpus of 639 titles and abstracts issued from The MEDLINE
bibliographical base [1]. Citations related to food-drug interactions
has been collected from MEDLINE in December 2013 with the following
query:

```
("FOOD DRUG INTERACTIONS"[MH] OR "FOOD DRUG INTERACTIONS*") AND ("adverse effects*")
```

This corpus is called POMELO, namely grapefruit in French, because has
been built and annotated during the French MESHS-funded project
POMELO.

The titles and abstracts has been manually annotated in order to make
explicit the information on food/drug interactions. The annotation
schema is described in [6]. Two experts have been involved in the
annotation process: one resident and one medical doctor. The
annotation has been done mainly by the resident, who was helped by the
medical doctor when facing difficult situations. The annotation has
been performed with the BRAT software [2,3].


## 2. Repository Structure

POMELO/README.md
	Current readme file

POMELO/corpus
        Directory containing the corpus in text format and the
        annotations in Brat format [3], but also the brat
        configuration files (annotation.conf, tools.conf, visual.conf)


## 3. Acknowledgements

If you use the POMELO corpus, please cite the following paper:

Thierry Hamon and Vincent Tabanou and Fleur Mougin and Natalia Grabar
and Frantz Thiessard. POMELO: Medline corpus with manually annotated
food-drug interactions. Proceedings of Biomedical NLP Workshop
associated with RANLP 2017. pages 73-80. September 2017. Varna,
Bulgaria

This work was supported by the MESH emergent project POMELO [4] and
Agence Nationale de la Recherche through the grant ANR-16-CE23-0012
France (project MIAM) [5].


The BibTeX citation is:

```
@InProceedings{Hamon&al2017b,
  author = 	 {Thierry Hamon and Vincent Tabanou and Fleur Mougin and Natalia Grabar and Frantz Thiessard},
  title = 	 {POMELO: Medline corpus with manually annotated food-drug interactions},
  booktitle =    {Proceedings of Biomedical NLP Workshop associated with RANLP 2017},
  year = 	 {2017},
  pages = 	 {73-80},
  month = 	 {September},
  address = 	 {Varna, Bulgaria},
}
```


## 4. License

This work (the annotations) is licensed under the Creative Commons
Zero v1.0 Universal.

## 5. References

[1] https://pubmed.ncbi.nlm.nih.gov/

[2] Pontus Stenetorp, Sampo Pyysalo, Goran Topić, Tomoko Ohta, Sophia
Ananiadou, and Jun’ichi Tsujii. 2012. brat: a web-based tool for
nlp-assisted text annotation. In Proceedings of the Demonstrations at
the 13th Conference of the European Chapter of the Association for
Computational Linguistics. Association for Computa- tional
Linguistics, Avignon, France, pages 102–107.
http://www.aclweb.org/anthology/E12-2021.

[3] http://brat.nlplab.org/

[4] http://natalia.grabar.free.fr/POMELO/

[5] https://miam.limsi.fr/

[6] Thierry Hamon and Vincent Tabanou and Fleur Mougin and Natalia
Grabar and Frantz Thiessard. POMELO: Medline corpus with manually
annotated food-drug interactions. Proceedings of Biomedical NLP
Workshop associated with RANLP 2017. pages 73-80. September
2017. Varna, Bulgaria
