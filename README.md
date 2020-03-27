## Read it on Reddit: LSTM Networks for Text Classification

### Team: [Luis Ulloa](https://github.com/ulloaluis), [Tassica Lim](https://github.com/tassicalim), [Tatiana Wu](https://github.com/tatianawu)

**Note**: We have modified the following notebooks to use a very small subset of the data (1%) so that the code can be run in a reasonable amount of time (since we train neural networks). Models using GloVe will still take at least 8-10 minutes because that's how long it takes to load in GloVe. No notebook should take longer than 20 minutes when using the small subset of data. We provide our original notebooks which use the entire dataset later in the README, and these notebooks take several hours to complete (no more than 8 hours).

**INSTRUCTIONS**:

Go to each of the following notebooks and hit "Run all." You will have to authenticate your account with the Google API (follow the instructions printed by the first cell), and then the entire notebook will execute.

**Data Preprocessing:**
https://colab.research.google.com/drive/1orgSILVEorUr_-5OPQLqxh72KdrO-_BR

* This creates the preprocessed dataframe and saves it to a pickle file, which is loaded into all of the model notebooks.

**Baseline Models:**
https://colab.research.google.com/drive/1qEfvi8Cq9iTUeQeXpo6M1rT3Sfvy2n14

* This notebook includes three baseline models
  * Multinomial naive Bayes with BOW
  * Multinomial logistic regression with BOW
  * Multinomial logistic regression with GloVe

**LSTM:**
https://colab.research.google.com/drive/1EF6Z-n45sXlplSFYRYYepmhVVTOs4fto

**CNN-LSTM:**
https://colab.research.google.com/drive/18QjnOvUxqSgXacPkoCDvblfm5d8Kk1p1

**CNN-LSTM-GloVe:**
https://colab.research.google.com/drive/1HVCwipWpbki70I4Ne59RkFItgvIsb5pb


**Note:** The Google Drive folder referenced in all of the above notebooks can be found here: https://drive.google.com/drive/folders/14tU-G6FUzbQDRruounj-ZZsgZPPNsC23?usp=sharing

---

For reference, here are the original five notebooks that run on the entire dataset. You can run these the same as the ones above, but each will take several hours due to the large dataset and computationally expensive models.

**Data Preprocessing:**
https://colab.research.google.com/drive/1MJloKbB0S0aMxsICJmf82ED2ymDTUtMG

**Baseline Models:**
https://colab.research.google.com/drive/1fWys4PDg5oisFRu9Xinw8HIj4OWxc1yn

**LSTM:**
https://colab.research.google.com/drive/1eNZqXqhOCrdg_eivKkEhVPqzME2blbS6

**CNN-LSTM:**
https://colab.research.google.com/drive/1sDTZWnmkXrR-C_HXm_2B5wTJGdCfI5fQ

**CNN-LSTM-GloVe:**
https://colab.research.google.com/drive/1yfNhs2W_s3MFy_i-bbDZeVN0Mp8j_8lk

---

### Other Notebooks / Google Drive:

**Data Visualization:**
https://colab.research.google.com/drive/1xQS_OzOBuBtuS1NTyhxVJ_IZVuWOtnOf

**Google Drive folder:**
https://drive.google.com/drive/folders/1m-0Rvr6oOszKdWPmHN1tM0lQHKUke5oD?usp=sharing

---

Notes

* We provided notebooks that run on a subset of data due to this Piazza post: https://piazza.com/class/jzhx357491j6nw?cid=1799

* The oracle was a human, so that work was done by hand and does not have a separate notebook.

* The full dataset (not pre-processed) can also be found here: https://www.kaggle.com/mswarbrickjones/reddit-selfposts

* All of the above notebooks are now view only (grading has passed). If you wish to run the code, you will have to make copies of the notebooks and potentially update the drive folder id with one of your own. You may or may not have to download the dataset yourself and place it in that google drive folder (and all relevant code changes associated with that).
