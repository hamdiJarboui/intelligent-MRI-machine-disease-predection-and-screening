# intelligent-MRI-machine-disease-predection-and-screening
intelligent MRI machine: disease predection and screening¶ general presentation of the project Following an absence of medication for certain diseases, it is always necessary to provide them at a precausal stage in order to increase the chances of recovery. This is why we thought of creating a Detection and screening model from imaging for example if a patient consults a rheumatologist for a skull fracture and the latter recommends an MRI our program is able to detect a tumor at the level of the brain if it exists. Not only that, MRIs do not generally provide all the information sufficient to make the diagnosis! Our program will lend a hand to help:  The radiologist: to recommend a specialist medcin: for a better diagnosis patient: for early detection of illness  that's why we collected a dataset from several datasets such as brain-tumor, alzheimer, covid_19, chest tumor (due to the time constraint we just collected a dataset of MRI images of 4 different types of disease but we can give a huge database of all diseases since the algorithm has shown these performances) so that the MRI can detect all types of diseases in an automatic way so a patient will be able to make a general diagnosis without the intervention of the doctor after a few minutes.  then we built the deep learning model based on CNN then we built the human machine interface which will be implemented on the MRI scanner
market research

after a study of the existing we noticed that all the algorithms treat a single type of disease (brain cancer only for example) from here we thought of an algorithm encompassing all types of diseases that can be detected by MRI

the steps followed in the code:

I - creation of the dataset
1- collection of datasets of diseases that can be detected by the MRI scan
2- creation of the global dataset which includes all the datasets to collect
3- cleaning of the global dataset
4- resizing the images
5- visualization of the dataset
II- creation of the machine learning model
1- learn the deep learning learning model
2- evaluation of the model
3- manual test of the model and visualization of the images
4- registration of the model
III- creation of the man-machine interface
IIII- test and validation of the application
(the man machine interface is developed on pycharm with the model created but we put all the code in the notebook sheet so that all the code is clear)

Dataset resources¶
https://www.kaggle.com/legendahmed/alzheimermridataset
https://www.kaggle.com/hamdijarboui/comp-tition-script/edit
https://www.kaggle.com/mohamedhanyyy/chest-ctscan-images
https://www.kaggle.com/luisblanche/covidct
https://www.kaggle.com/hamdallak/the-iqothnccd-lung-cancer-dataset
