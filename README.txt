Please Unzip the File. Do not move any documents outside of the file. 

Running the Model:
1. Ensure that the NLTK library is downloaded and accessible. You can do
   this by opening Anaconda Prompt and running the following line of code:
--------------------------------------------------------------------------   
conda install -c anaconda nltk
--------------------------------------------------------------------------
2. Run the first two cells, the output to the second cell should be True.
   If there are no errors in running these cells then the code can be run.
3. Run all code cells under the heading 'The Model'. This contains the code 
   used to preprocess, train, predict and evaluate the test data

Test Data for the Model:
1. Run the code cell under the heading 'Testing the Model'. To ensure this
   works on your laptop and correctly outputs the .csv file to the correct 
   location, replace 
---------------------------------------------------------------------------
C:\\Users\\61413\\Documents\\Machine Learning\\Assignment2\\A2_prediction14.csv
---------------------------------------------------------------------------
   with the target directory and output name (A2_prediction14.csv) 
   on your personal laptop as required. 

Evaluating the Variables Used in the Model:
1. Test the Accuracy Given a Variation in Feature Dimensionality contains
   a cell which determines why no feature dimensionality reduction was used. 
   This is explained in the report. 
2. Test the Accuracy Given Variation in N-Gram Range contains a cell which
   determines why the n-gram range was [1,3]. This is explained in the report.
3. Distribution of Text Size in Training Data and Training Errors contains
   the distribution of Text Size in Training Data and Errors in the 
   Training data to determine that the model underperforms with larger text
   reviews. This is explained in the report. 