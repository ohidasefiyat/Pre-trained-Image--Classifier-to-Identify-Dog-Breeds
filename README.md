# Pre-trained-Image--Classifier-to-Identify-Dog-Breeds
Principal Objectives
1. Correctly identify which pet images are of dogs (even if breed is misclassified) and which pet images aren't of dogs.
 
2. Correctly classify the breed of dog, for the images that are of dogs.
 
3. Determine which CNN model architecture (ResNet, AlexNet, or VGG), "best" achieve the objectives 1 and 2.
 
Consider the time resources required to best achieve objectives 1 and 2, and determine if an alternative solution would have given a "good enough" result, given the amount of time each of the algorithms take to run.

**Program Outline**
Time your program
Use Time Module to compute program runtime
Get program Inputs from the user
Use command line arguments to get user inputs
Create Pet Images Labels
Use the pet images filenames to create labels
Store the pet image labels in a data structure (e.g. dictionary)
Create Classifier Labels and Compare Labels
Use the Classifier function to classify the images and create the classifier labels
Compare Classifier Labels to Pet Image Labels
Store Pet Labels, Classifier Labels, and their comparison in a complex data structure (e.g. dictionary of lists)
Classifying Labels as "Dogs" or "Not Dogs"
Classify all Labels as "Dogs" or "Not Dogs" using dognames.txt file
Store new classifications in the complex data structure (e.g. dictionary of lists)
Calculate the Results
Use Labels and their classifications to determine how well the algorithm worked on classifying images
Print the Results
You will need to repeat these tasks for each of the three image classification algorithms that are provided to you.

**Questions regarding Uploaded Image Classification:**

1. Did the three model architectures classify the breed of dog in Dog_01.jpg to be the same breed? If not, report the differences in the classifications.

Answer: Alexnet model Architecture classify the breed of dog_01.jpg as :  timber wolf, grey wolf, gray wolf, canis lupus
		resnet model architecture Classify the breed of dog_01 as: pug, pug-dog
        vgg model architecture Classify the breed of dog_01 as: pug, pug-dog


2. Did each of the three model architectures classify the breed of dog in Dog_01.jpg to be the same breed of dog as that model architecture classified Dog_02.jpg? If not, report the differences in the classifications.

Answer: The three model architecture classify the breed of dog in dog_01.jpg as the same breed of dog as that pf model architecture classified dog_02 as given above


3. Did the three model architectures correctly classify Animal_Name_01.jpg and Object_Name_01.jpg to not be dogs? If not, report the misclassifications.

Answer: yes the three model architecture classified them as not dog


4. Based upon your answers for questions 1. - 3. above, select the model architecture that you feel did the best at classifying the four uploaded images. Describe why you selected that model architecture as the best on uploaded image classification.

Answer:The model architecture that did best in classifying the images is vgg model for the reasons below:
	1. The run time is faster than the first two thereby increasing performance
    2. It correctly tell the number images that matches unlike the other two that predicted that no matches or just one match
    3. hence it out performed the other two since it predicted the images dog and not dog %100 of time

References:
https://datatofish.com/dictionary-to-dataframe/
all hints given for each of the exercise
https://github.com/sixhobbits/udacity-image-class-project/blob/master/intropyproject-classify-pet-images
https://www.w3schools.com/python/python_lists_comprehension.asp
