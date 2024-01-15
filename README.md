# BraTS-Challenge
Bachelor's thesis at Novosibirsk State University: Brain tumor segmentation and prediction of patient state using data from http://braintumorsegmentation.org/. 

The project included two tasks.

1) Brain Tumor Segmentation:
For this task I explored a variety of Neural Networks, including U-Net, Ternaus-Net, DeepLabV3, Pix2Pix. Additionally, I experimetned with diverse loss functions (linear combinations of BCE, Dice loss, focal loss) and augmentations. The best model was U-Net with focal augmentations and BCE-Dice loss function. The segmentation of brain tumors was successfully executed, achieving Dice coefficient of 0.818. This outcome underscores the precision and accuracy of the model.

2) Prediction of Patient's Lifespan Interval:
The second task involved predicting the time interval of a patient's life, employing segmentation features for multi-class classification. In this task, I used feature extraction using the nibabel package. For the classification task, I used a Random Forest Classifier and implemented forward feature selection and cross-validation for parameter tuning. The model demonstrated its predictive capability with an F1 metric of 0.586. This metric reflects the model's proficiency in classifying different lifespan intervals, highlighting its potential for valuable clinical applications.

The project's code can be found in the accompanying notebooks and a detailed explanation of the tasks, solutions, and results can be found in the paper.

<img width="612" alt="image" src="https://user-images.githubusercontent.com/122701199/212501700-cdabc6cb-2773-42ae-83ea-736a8cc10aa4.png">

