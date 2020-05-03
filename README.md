# Kaggle-iFood-Challenge-Rice-University
Detail description is here: https://www.kaggle.com/c/ifood-rice/overview
ifood_train.ipynb:
Conatin the code for training.

Data:
    imagDataset: Class. Load the data 
    get_data_set: function. Load data and do data preprocessing 
    
Train:
    Train: Main function. Train the model and save result
    load_model: Load the saved model

Chain model and pretrained model:
    Define the chian model. Combination of CovNet and FNN 
    initilize_pretrained_model,initilize_pretrained_chain_model: Initalize pretrained model 
    initilize_optimizer: SGD optimizer. Decide whether only train the fully connected layers or all layers.

Aux:
    check_accuracy: function. Check the accuracy on the validation set 
    LabelSmoothingLoss: Define the lable smoothing loss modules (Code from Internet)
    
    
tune_and_generate_test_result.ipynb: 
Generate the prediction on test set. Using ensemble method
    get_test_data: Get test data from three types of data pre-processing.
    print_predict: Print prediction, using ensemble method. 
    
    
