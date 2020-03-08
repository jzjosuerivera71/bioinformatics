<h1 align="center">Bioinformatics</h1>

## Level 1: Nucleotide sequence
- Data from **DNA** or **RNA**.
- 4 letters: **A**, **C**, **G**, **T**
- K-mers: "words" of K-length. Ej. (hexamers), "ATGCATGCA" becomes: ‘ATGCAT’, ‘TGCATG’, ‘GCATGC’, ‘CATGCA’.

## Level 2: Amino acids sequence
- Data from **Proteins**.
- 21 letters: **A**, **R**, **N**, **D**, **C**, **Q**, **E**, **G**, **H**, **I**, **L**, **K**, **M**, **F**, **P**, **S**, **T**, **W**, **Y**, **V**
- Datasets
  - Kaggle
    - [400000 protein data set](https://www.kaggle.com/shahir/protein-data-set) (146 MB)
  - [UniProt databases](https://www.uniprot.org/help/about)
    - UniProt Knowledgebase (UniProtKB)
    - UniProt Reference Clusters (UniRef)
    - [UniProt Archive (UniParc)](https://www.uniprot.org/help/uniparc)

<p align="center"><img width="400" src="img/aminoacids.svg"/></p>


## Level 3: Domains of proteins

<p align="center"><img width="400" src="https://genetics564.weebly.com/uploads/8/6/5/7/865764/101986_orig.gif"/></p>

## Level 4: 3D shape of proteins
![](/img/protein-process.svg)

## Level 5: Gen Ontology
- **GO**
- **Uniprot**

## Reactoma
**Grafo de interacción** de proteinas.


### BLAST
**B**asic **L**ocal **A**lignment **S**earch **T**ool. Algoritmo que determina el **nivel de similaridad de 2 secuencias**. Puede usarse:
- A nivel de secuencias de nucleótidos (Nucleutide BLAST)
- A nivel de secuencias de aminoácidos (Protein BLAST)


---

<h1 align="center">Deep Learning Bioinformatics</h1>


## Step 1: Traditional methods
- Count vectorizers with n-grams
- 1D convolution
- Read [AlphaFold](https://deepmind.com/blog/article/AlphaFold-Using-AI-for-scientific-discovery)


## Step 2: Recurrent methods
- [Kaggle: LSTM with keras](https://www.kaggle.com/danofer/protein-sequence-family-classification)
- [UDSMProt](https://github.com/nstrodt/UDSMProt)

  
## Step 3: Transformers
- **Read [Biological structure and function emerge from scaling unsupervised learning to 250 million protein sequences](https://doi.org/10.1101/622803)**: After training the Transformer algorithm to process amino acid sequences, researchers looked at the embedding learned by the model. Above all, they found out that the neural network had built a complex representation of the input sequences. This in turn reflects their biological properties such as activity, stability, structure, binding etc. In other words, the deep learning algorithm learned important biochemical properties characterising the different amino acids and proteins, all by itself, without any supervision.
- [Illustrating the Reformer](https://towardsdatascience.com/illustrating-the-reformer-393575ac6ba0)
- [Advices for training transformers](https://twitter.com/Eric_Wallace_/status/1235616760595791872)
- [Kaggle winner solution to Google’s QUEST Q&A Labeling](https://medium.com/kaggle-blog/the-3-ingredients-to-our-success-winners-dish-on-their-solution-to-googles-quest-q-a-labeling-c1a63014b88): BERT, RoBERTa, BART
- Andrés Solution to [Predicting Molecular Properties](https://www.kaggle.com/c/champs-scalar-coupling)
  - [**Summary**](https://www.kaggle.com/c/champs-scalar-coupling/discussion/106468)
  - [**Code**](https://github.com/antorsae/champs-scalar-coupling)

## Step 4: 3D Proteins
- 3D protein


### Python packages
- [biopython](https://biopython.org/)
- [scikit-bio](http://scikit-bio.org/)

### Learn Resources
- [Rosalind](http://rosalind.info)
- [Bioinformatic salgorithms](http://bioinformaticsalgorithms.com)
- [Readiab](http://readiab.org)
