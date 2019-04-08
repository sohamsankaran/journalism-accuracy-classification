# journalism-accuracy-classification
Classifications of the accuracy of journalistic content 

---

[At the Edge of Deception](https://soh.am/writes/at_the_edge_of_deception) lays out the following taxonomy of journalistic accuracy:

><p>Plainly incorrect (Type 1): the article gets at least one important fact egregiously wrong.</p>
><p>Misleading (Type 2): The article does not directly get important facts wrong, but induces incorrect beliefs in the minds of readers through framing and/or omission.</p>
><p>Correct (Type 3): The article does not get anything (at least anything important) wrong and does not mislead.</p>


This repository was established to build out a database of journalism classified by accuracy type. 

Please add in new articles to articles.csv via pull request. At the moment, articles about science or social science are preferred, but feel free to add in ones of different categories. For articles of Type 1, ensure that include a link to some reasonably authoratative proof of incorrectness under `incorrectness_proof`. For articles of Type 2 or Type 3, if you have experimental evidence than an article induces incorrect beliefs, or that it doesn't, set `experimentally_tested` to `true` for the article and link to your evidence under `experiment_link`. If you strongly suspect that an article induces incorrect beliefs, set `experimentally_tested` to `false` and leave the `experiment_link` field blank -- note that these fields are all optional for Type 1. 
