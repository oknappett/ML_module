Running the notebooks again: 

	load into collab, run the top cell (! mkdir ~/.kaggle etc...) which loads the kaggle dataset into the collab run time

if running in kaggle:
	
	Do not run the cell described above, change all values of read in data to the kaggle dataset before running.

!GOOGLE COLLAB! 

for the signal approach, sometime the runtime runs out of RAM. An attempt has been made to delete variables/objects once they are no longer needed but sometimes the runtime fails around the 3rd experiment. 
If this happens, run the cells which declare the pre-processing functions replace_outliers_with_nan(), preprocess(), create_train_test(), create_cnn_model() and then run the failed experiment again. 