# DoAn3_Car_Classification_PyTorch
Advisor: Master Hoàng Long

Student 1: Nguyễn Mai Hùng,
StudentId: 16110098

Student 2: Phạm Hoài Phong,
StudentId: 16110179

***Making a car classifier using Pytorch
=> In this notebook, we are making a car classifier using the Stanford car dataset, which contains 196 classes. I'll be using a pre-trained resnet34 with transfer learning to train the model. All layers will be fine tuned and the last fully connected layer will be replaced entirely.

###Dataset (196 classes):
+ Train folder: 8144 images, avg: 41.5 images per class.
+ Test folder: 8041 images, avg: 41.0 images per class.

Steps
+ Step 1: Load the data and transform dataset
+ Step 2: Create a Model training function
+ Step 3: Evaluate training data
+ Step 4: Create a Model
+ Step 5: Train Model
+ Step 6: Save the Model
+ Step 7: Load the Model
+ Step 8: Draw plot the stats
+ Step 9: Predict the Image
+ Step 10: Show the result

Reference
+ https://www.kaggle.com/deepbear/pytorch-car-classifier-90-accuracy
