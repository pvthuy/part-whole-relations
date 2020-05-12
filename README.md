# A DATASET of PART-WHOLE RELATIONS (MERONYMY)

This is the dataset for the ACL2018 paper:

"Van-Thuy Phi, Joan Santoso, Masashi Shimbo and Yuji Matsumoto. *Ranking-Based Automatic Seed Selection and Noise Reduction for Weakly Supervised Relation Extraction*. Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics."

There are no datasets available for all fine-grained subtypes of the PART-WHOLE relation so far. WordNet provides some semantic relations, such as *synonymy*, *hypernonymy*, and *meronymy*. From examples of meronymy (or the part-whole relation), part-whole pairs are divided into Part-Of, Member-Of, and Substance-Of sub-categories. Nevertheless, they do not cover the variety of the part-whole relationship.

We provide an annotated dataset of part-whole relations as a reliable resource for selecting seed sets. The part-whole relation includes following subtypes:
1.	*Component-Of*
2.	*Member-Of*
3.	*Portion-Of*
4.	*Stuff-Of*
5.	*Located-In*
6.	*Contained-In*
7.	*Phase-Of*
8.	*Participates-In*

We use the above part-whole taxonomy as it is well-structured, clearly-presented, and it contains all subtypes in previous ontological studies (see [Phi and Matsumoto, 2016](http://www.aclweb.org/anthology/Y16-2015) for details).

FORMAT of the annotation file:
- *1stEntity*
- *Pattern*
- *2ndEntity*
- *1stEntity - normalized*
- *Pattern - normalized*
- *2ndEntity - normalized*
- *A source sentence* which contains the above triple <1stEntity, Pattern, 2ndEntity>
- *A source URL* (The paragraph/The full article which contains the relation triple can be obtained from this URL)
- *Subtype* of the triple
- *Order*: Part-Whole / Whole-Part.
