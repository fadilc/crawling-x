# crawling-x

how to extract tweet data from X with no limitation. 

https://colab.research.google.com/drive/11cyL2GVKIZyY1-O4RNrQnsz6XtNikmNV?usp=sharing#scrollTo=LYDR51dJlVlX

found this ipynb from talented FTD Helmi Satria https://github.com/helmisatria w/ a little bit modification

I used this to made a datasets for sentiment analytics exams at my f****** college

![image](https://github.com/fadilc/crawling-x/assets/118906826/b135efa2-a24a-473e-b184-0a9ffd41a596)

firstly, put the twitter auth code that u  can find from this step:
![image](https://github.com/fadilc/crawling-x/assets/118906826/9dc56b36-c0b8-4962-a2e5-12b55c77c918)
open ur twitter page - right click and then click inspect - click application in top toolbar - find cookies in left section then click https/twitter.com - in the  center menu find auth_token then copy the code in the bottom of it.

paste to twitter auth code cell then run 

![image](https://github.com/fadilc/crawling-x/assets/118906826/5fdd7e6c-bd9c-42a3-9ae8-42016d768178)
then run the cell below to install pandas & node.js. wait until finished

![image](https://github.com/fadilc/crawling-x/assets/118906826/28a70a6b-172c-4c68-adfa-07d23199f1bc)
then put ur filename to store urmade dataset and the keyname of ur theme research that u want to find in tweets. put 'lang:id' if u want to filter indonesian only. and fill the limit number as how much that u want to extract. Run it!
it took long time so kindly wait until finished.

![image](https://github.com/fadilc/crawling-x/assets/118906826/bee70e53-afb9-4558-8f99-6b3349069710)
after finished. u can check the sample of extracted twitter data with running this code sell

![image](https://github.com/fadilc/crawling-x/assets/118906826/5b41e43e-d229-4e44-8e11-10ad93cf3881)
to downloading ur extracted raw datasets in this menu at the right side of collabs. tweets data - 'ur filename'.csv - right click and download.









