Decision Tree - Bank Marketing Dataset
Description
You are given the 'Portuguese Bank' marketing dataset which contains data about a telemarketing campaign run by the bank to sell a product (term deposit - a type of investment product). 

Each row represents a 'prospect' to whom phone calls were made to sell the product. There are various attributes describing the prospects, such as age, profession, education level, previous loans taken by the person etc. Finally, the target variable is 'purchased' (1/0), 1 indicating that the person had purchased the product. A sample of the training data is shown below (note that 'id' shouldn't be used to train the model) :

    age          job  marital          education default  housing     loan  \
0   30  blue-collar  married           basic.9y      no      yes       no   
1   39     services   single        high.school      no       no       no   
2   25     services  married        high.school      no      yes       no   
3   38     services  married           basic.9y      no  unknown  unknown   
4   47       admin.  married  university.degree      no      yes       no   

     contact month day_of_week ...  pdays  previous     poutcome  \
0   cellular   may         fri ...    999         0  nonexistent   
1  telephone   may         fri ...    999         0  nonexistent   
2  telephone   jun         wed ...    999         0  nonexistent   
3  telephone   jun         fri ...    999         0  nonexistent   
4   cellular   nov         mon ...    999         0  nonexistent   

   purchased  id  
0          0   1  
1          0   2  
2          0   3  
3          0   4  
4          0   5  

As an analyst, you want to predict whether a person will purchase the product or not. This will help the bank reduce their marketing costs since one can then target only the prospects who are likely to buy.

Build a decision tree with default hyperparameters to predict whether a person will buy the product or not. 

The training data is provided here:
/data/training/bank_train.csv

After you train the model, use the test data to make predictions. The test data can be accessed here. 
/data/test/bank_test.csv

You have to write the predictions in the file
/code/output/bank_predictions.csv

in the following format (note the column names carefully):
     bank_predicted    id
0               0  2041
1               0   399
2               0  1400
3               0  3709
4               0  2111




Datasets
Training dataset
Validation dataset
