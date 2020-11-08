# heart_datasets_ML
Heartbeat classification (>90% accuracy, >95% CV score, >90% precision recall and f score), and disease detection(>80% accuracy) <br>


**Author** <br>
> Simone Maria Giancola <br>
[Email](simonegiancola09@gmail.com)<br>
+39 3314788683 <br>
Linkedin Profile: [Simone Giancola](https://www.linkedin.com/in/simone-maria-giancola-011465173/) <br> 
Github Profile: [@simonegiancola09](https://github.com/simonegiancola09) 

I am absolutely not a professional, so any suggestion, either typo, code, writing, or analysis related is highly appreciated, and will be welcomed with enthusiasm. <br>

**IMPORTANT**
> Being quite big, my Jupyter environment did not load a table of contents at the beginning, making it very difficult to navigate the document. Gooogle Colab has a built in table of contents on the left.  This also makes Jupyter reading kind of painful since I put numbers to heading by hand and they would not match those of Jupyter. If Colab does not open there is also a link to NbViewer below for both documents:
  *[Disease detection](https://nbviewer.jupyter.org/github/simonegiancola09/heart_datasets_ML/blob/main/disease_detection/heart_disease_1.ipynb)
  *[Heartbeat categorization](https://nbviewer.jupyter.org/github/simonegiancola09/heart_datasets_ML/blob/main/heartbeat_categorization/heartbeat_categorization.ipynb)


> The second dataset is definitely more interesting, and has better results, so I suggest giving a look at it after having skimmed the method in the first dataset, without spending too much time on it. I would also point out that most of the models I found online had a higher accuracy but a low CV score (around 30% less), meaning less reliability. My model, though less accurate, seems to be more robust. <br>

While attending university I had the opportunity to learn the basics of Python and some of its libraries. This is one of the attempts of satisfying my personal taste with projects that could also be useful. <br>
After having attended the Machine Learning course at Bocconi University, I felt motivated enough to apply the knowledge acquired in the healthcare setting. <br>
[Kaggle](https://www.kaggle.com/) was a good starting point. There I found the two datasets I will work with in the following notebook. The first one is rather small, while the second one is definitely of higher size. More information can be found at the following links: <br>
   * [Disease detection](https://www.kaggle.com/cherngs/heart-disease-cleveland-uci) <br>
   * [Heartbeat categorization](https://www.kaggle.com/shayanfazeli/heartbeat?select=mitbih_train.csv) <br>

> Technical and knowledge sources vary from across the internet, libraries documentation, and lecture notes of the Python courses I had at Bocconi University. The framework, notation and main idea recalls that of the Machine Learning course I already mentioned, which used as a textbook: "_Hands on Machine Learning with Scikit-learn Keras and Tensorflow_". <br>

In order to avoid writing an enormous document, I leave to the writer the option to review data sources, description of features and acknowledgements. The first dataset in particular had 4 or 5 missing values that were adjusted by a user who cleaned the file and shared it with the public (all explained on the link provided). <br>
I will develop a process of thought to analyze data and then apply it to both scenarios, adapting it to the needs of each piece of information, to see its results. <br> 

In the event that the reader is curious of the result only, I suggest skipping all chapters up to "Pipeline and Ensemble" for both datasets. I will present my reasoning with words and numbers, with more details than a simple script. I suggest to give at least a look at data visualization cells across the whole notebook.  <br>

