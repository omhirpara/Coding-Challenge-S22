# Updated README file

**Libraries used:** numpy, pandas, scikit-learn, tensorflow, matplotlib

**Explanation:**

First the dataset was converted into numerical data, or rather each letter was given an "ID". Because the target variable is the class (whether the mushroom is edible or poisonous), it was removed from the data set. Next, all the non-numerical data (basically the entire data set) was turned into numerical data. Next, the data was split into training and testing data with a 70-30 split. 70% was reserved for training and 30% was reserved for testing. After splitting the data set, it was standardized using the scikit-learn library. Then the model was trained for 100 epochs while also recording accuracy, precision, and recall. the metrics were then graphed to visualize how loss, accuracy, precision, and recall fluctuated during the training cycle. Finally, using the prediction, the test data was given a 1 if the mushroom was edible or 0 if the mushroom was poisonous. 

**Resources used:**

Code for the entire algorithm except converting the dataset into numerical form was used from this video: https://www.youtube.com/watch?v=r3aZBohotF8&t=232s

Code for converting the dataset into numerical form was used from this video: https://www.youtube.com/watch?v=j6jstahQp2A


**Note:** 
This is the first time I have attempted to solve a machine learning problem. Therefore, I am not sure if the approach I used to solve the problem is valid, which means the solution is inaccurate. Moreover, I did not know how to properly convert the letters in the dataset into a numerical form, so I assigned them "IDs" based on the second video noted above.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
# ACM Research Coding Challenge (Spring 2022)

## [](https://github.com/ACM-Research/-DRAFT-Coding-Challenge-S22#no-collaboration-policy)No Collaboration Policy

**You may not collaborate with anyone on this challenge.**  You  _are_  allowed to use Internet documentation. If you  _do_  use existing code (either from Github, Stack Overflow, or other sources),  **please cite your sources in the README**.

## [](https://github.com/ACM-Research/-DRAFT-Coding-Challenge-S22#submission-procedure)Submission Procedure

Please follow the below instructions on how to submit your answers.

1.  Create a  **public**  fork of this repo and name it  `ACM-Research-Coding-Challenge-S22`. To fork this repo, click the button on the top right and click the "Fork" button.

2.  Clone the fork of the repo to your computer using  `git clone [the URL of your clone]`. You may need to install Git for this (Google it).

3.  Complete the Challenge based on the instructions below.

4.  Submit your solution by filling out this [form](https://acmutd.typeform.com/to/uTpjeA8G).

## Assessment Criteria 

Submissions will be evaluated holistically and based on a combination of effort, validity of approach, analysis, adherence to the prompt, use of outside resources (encouraged), promptness of your submission, and other factors. Your approach and explanation (detailed below) is the most weighted criteria, and partial solutions are accepted. 

## [](https://github.com/ACM-Research/-DRAFT-Coding-Challenge-S22#question-one)Question One

[Binary classification](https://en.wikipedia.org/wiki/Binary_classification) is a type of classification task that labels elements of a set (i.e. dataset) into two different groups. An example of this type of classification would be identifying if people had a specific disease or not based on certain health characteristics. The dataset found in `mushrooms.csv` holds data (22 different characteristics, specifically) about different types of mushrooms, including a mushroom's cap shape, cap surface texture, cap color, bruising, odor, and more. Remember to split the data into test and training sets (you can choose your own percent split). Information about the meaning of the letters under each column can be found within the file `attributelegend.txt`.

**With the file `mushrooms.csv`, use an algorithm of your choice to classify whether a mushroom is poisonous or edible.**

**You may use any programming language you feel most comfortable. We recommend Python because it is the easiest to implement. You're allowed to use any library or API you want to implement this, just document which ones you used in this README file.** Try to complete this as soon as possible.

Regardless if you can or cannot answer the question, provide a short explanation of how you got your solution or how you think it can be solved in your README.md file. However, we highly recommend giving the challenge a try, you just might learn something new!
