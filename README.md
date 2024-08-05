Note : The bilinear loading dataset used for trainings in this research was generated in the previous research, which can be downloaded here: https://doi.org/10.1016/j.ijsolstr.2023.112592

# Convolutional (CNN) - Recurrent Neural Networks (RNN) - Transformers :

	* The codes related to training experiments on a bilinear loading dataset using CNN, RNN and Transformer based  
  	  Neural Network (NN) architectures are located in the Jupyter notebooks:

		- PyTorch : CNN_RNN_Transformers_0_10000_parameters_Training_Codes_PyTorch_version.ipynb 

		- TensorFlow : CNN_RNN_Transformers_0_10000_parameters_Training_Codes_TensorFlow_version.ipynb

	* The training results based on different structured NN architectures are in the folder :
	
		- CNN_RNN_Transformers_Training_Results

	* Plotting codes used to analyse training results are included in the notebook :

		- CNN_RNN_Transformers_Paper_Plottings.ipynb


# Synthetic Dataset and Training Experiments :

	* Synthetic paths generation, proposed consistent RNN cell and GRU based NN architectures training codes are in notebooks :

        	- Synthetic_Data_Generation_Training_Experiments/Synthetic_Paths_Generation_Training_and_Test_Sets.ipynb

        	- Synthetic_Data_Generation_Training_Experiments/Consistent_RNN_Cell_Synthetic_Dataset_Trainings_and_Results.ipynb

	* The weights from trained NN architectures are in the folder : 
		
		- Synthetic_Data_Generation_Training_Experiments/Weights

	* Synthetic Normalized Plastic Strain (NPS) predictions for different number of increments that are obtained from the 
	  trained NN architectures are in the folder :

		- Synthetic_Data_Generation_Training_Experiments/Predictions

	* The plotting codes are in notebook :

		- Synthetic_Data_Generation_Training_Experiments/Synthetic_Data_Paper_Plottings.ipynb


# Bilinear Loading Dataset and Training Experiments : 

	* Training experiments with a consistent RNN cell and GRU-based NN architectures on a bilinear loading dataset and 
          testing with 100000 increments Bilinear Forming Limit Curves (FLCs) are in notebook :
	
		- Bilinear_Forming_Limit_Curves_( FLCs )_Training Experiments/Consistency_Training_For_Forming_Limit_Curves(FLCs).ipynb
		
		- Bilinear_Forming_Limit_Curves_( FLCs )_Training Experiments/Standard_GRU_Training_For_Bilinear_Forming_Limit_Curves_(FLCs).ipynb

	* The weights and NPS predictions for different number of increments from trained NN architectures are in the folders :

		- Bilinear_Forming_Limit_Curves_( FLCs )_Training Experiments/Weights

		- Bilinear_Forming_Limit_Curves_( FLCs )_Training Experiments/Predictions

	* The plotting codes are in the notebook :

		- Bilinear_Forming_Limit_Curves_( FLCs )_Training Experiments/FLC_Paper_Plottings.ipynb


Note: Different trainings may give different results, so we recommend to re-run the experimental codes as Jupyter notebooks.
* 