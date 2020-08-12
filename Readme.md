# Fashion MNIST

My dream is to build an app that makes outfit recommendations based on my wardrobe. This is the first step.


The first step is recognizing and labeling items of clothing. The fashion MNIST data set (F_MNIST) includes 10 types of clothing which include: 
1. T-shirt/top 
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle boot

The benchmark accuracy for this dataset is 96.7% and using my methods I achieved 91.36% accuracy on my test set.

I used two convolutional blocks followed by two dense layers for my model. Each conv block is followed by MaxPooling and a Dropout.
