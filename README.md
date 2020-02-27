## Contents of This Repository
This is the repository for my undergraduate thesis 'The Measure of a Girl: Towards Vectorized Representations of Literary Character. Here are details for the files and folders in this repository:

The folder **code** contains three files:

Distance Experiments.ipynb contains the main code for this project i.e. the code for training Character2Vec and LDA-C, as well as all model evaluation code and results. 

anno_auto.ipynb contains the code which I used to process the outputs of the BookNLP quote attributor, which I used to attribute all quotes in the eight books in the *Anne of Green Gables* book series.

test_accuracy_annotation contains the code which I used to test the accuracy of the aforementioned annotator, by manually labeling 12.8% of the quotes in the first book of the series. 

The **raw_data** folder contains the text files for the eight books used in this project.

The **old_notebooks_for_reference** folder contains all deprecated code.

book.id.files.zip contains zipped outputs of the quote attribution annotator from BookNLP as used on my dataset.

gables_speakingwithtoken_list.txt, montgomery.gables.tokens and shuffled_annotable_gables.csv are necessary for testing the accuracy of the annotator.

utterance_listslabels_by_book.zip contains a further preprocessed versions of the dataset (into lists of quotes and labels).

## Pre-Trained CBB Vectors
The four sets of 100 experiments of pre-trained CBB vectors mentioned in the report can be located here: 
+ LDA-C CBB vectors (true dataset):https://drive.google.com/file/d/1k_uHqVNgxgGILS16E8s8qOfCFlo1d6Ef/view?usp=sharing
+ LDA-C CBB vectors: (shuffled dataset): https://drive.google.com/file/d/1d8KRGT-De4IX8jxj-2skaY5f5LIW1hCd/view?usp=sharing
+ Character2Vec CBB vectors (true dataset):https://drive.google.com/file/d/1-21slt8qoNQFyk6dC0aVVEB-mXHFAhXQ/view?usp=sharing
+ Character2Vec CBB vectors: (shuffled dataset):https://drive.google.com/file/d/1--k0BbgNDQLsEIYJ35rT9efU3fVNlQvz/view?usp=sharing
