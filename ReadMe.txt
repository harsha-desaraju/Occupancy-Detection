Member 1 : Desaraju Harsha Vardhan        
Member 2 : Mallidi Poorna Siva Rama Reddy 
Member 3 : Srinivasula Koushik            

This directory contains 
1) ModelTraining.ipynb
2) ModelTesting.ipynb

ModelTraining.ipynb trains the model and saves it to the drive.
ModelTesting.ipynb is for testing the model and comparing its performance with a pretrained model.

To run both ModelTraining.ipynb and ModelTesting.ipynb,
1) Upload the notebooks to the drive.
2) A folder containing the training data is already shared to you by "Mallidi Poorna Siva Rama Reddy" with name "Unbiased_Enthusiasts".
3) Right click on the folder and select "Add shortcut to drive".
4) Then select "My Drive".

Then both the notebooks can be run without any changes.

The folder Unbiased_Enthusiasts contains training data, saved model (our model) and pretrained model.

The directory structure of the shared folder:

							Unbiased_Enthusiasts 
								|
				______________________________________________________________________
				|								     |
			    Our_model                                                         Pretrained_model
				|								     |____ config file
	_________________________________________						     |____ model file
	|			      		|						     |____ labels file
   Saved_model                     	     Dataset
	|___ Pickled_Model.plk        		|
		          ____________________________________________
			  |		|               |            |
	      	      Test_data    Train_data       train.csv    test.csv
		 	  |             |
	      	      contains      contains
	    	    test images   training images


The link for the shared folder: https://drive.google.com/folderview?id=1sCcWYK7uCtmr17r2Vimjxq58b2-AnoFe
