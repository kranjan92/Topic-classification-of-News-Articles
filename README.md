# Topic-classification-of-News-Articles
Topic Classification: Hybrid Feature selection model using BPSO-MLP

## Why and What is Topic Classfication ?

The huge amounts of information assets exist in the form of unstructured text corpuses such as scientific articles, healthcare records, space problem reports and news feed corpora. Among these, the most popular use case in organising and recommending similar news articles based on the specific categories (topic areas) on a news website. Currently, a news website which provides a variety of news articles a day to users on a broad range of topic areas. To increase the user engagement and time span on the site, maybe one of the solutions is to recommend similar articles in an organised way. So, one must provide a way through to navigate and process all these corpora of reports for identifying the most popular topics and trending themes to deliver a prescriptive analytical result that adds a value to the business. But
this is all often poorly exploited. In order to achieve an effective classification model in processing and analysing the textual data by identifying relevant text features while reducing the access time which requires Topic classification models.

## Download Data set and Dataset Lineage 

URL: http://qwone.com/ jason/20Newsgroups/

# Details: 

This corpus contains a collection of 18k news feed articles of 20 different categories/topics that appeared in Usenet newsgroup collection. Two of the topics are distinct and the rest are closely related to each other. Apart from this, corpora have a huge set of lexicons and less usage of rhetorical writings.

For this Case considered only five categories that have collected documents as 4489 rows
of 5 set of classes were stored as shown below

News Topics Documents
Computer Science 973
Sports 994
Electronics 984
Politics 910
Religion 628
Total 4489
Table 1: News Documents

## Pre-requisits

System Requirements
Processor Intel(R)
Core(TM) i5-7300HQ CPU @2.50Ghz
Installed memory (RAM) 8GB
Hard disk (HDD) 500GB
Graphics Card (GPU) NVIDIA
GEFORCE -2GB
System Type 64bit
Operating system
Operating System Windows 10 OS

## Set up Anaconda Python

## Install Jupyter, NLTK and Neural Network Libraries

To install NLTK libraries NLTK 3.2.5 Documentation follow sequence of steps
shown below.

1. Open “anaconda command prompt” from windows
2. Type “python -m pip install nltk” install successfully. Note: while installing it may
ask for (Y/N) to continue, enter ’Y’ and proceed.
3. Further, open “Jupyter notebook”, create a new python shell by clicking “New”
button.
4. Run the code as shown below figure 2, After running the code a pop-up of “NLTK
downloader” window will visible as shown in figure 3.
5. Click to download button to install the all packages of NLTK.

## Install Tensor Flow and Keras

To install Neural network packages follow sequence of steps shown below.
1. Open “anaconda command prompt” from windows
2. Execute the following commands individually as shown below table 2. Note: while
installing it may ask for (Y/N) to continue, enter ’Y’ and proceed.
3. Make sure that all the packages are successfully installed.
conda install scipy
pip install sklearn
pip install pandas
pip install pandas-datareader
pip install matplotlib
pip install pillow
pip install requests
pip install h5py
pip install tensorflow ==1.8.0
pip install keras ==2.2..0

