# Support-vector-machine-project (SVM) (AI)
In this exercise, we will use ready-made SVM tools and libraries to get familiar with SVM classification capabilities.
First, design some two-class problems from very simple to very complex. For example, consider a number of points (for example, 100 to 1000 points) in two-dimensional space and assume that some points are members of class 1 and others are members of class -1. Plot the points on a two-dimensional graph. For example, the following figures can be some suggested examples:

![Annotation 2023-03-16 211812](https://user-images.githubusercontent.com/119484000/225891668-e282dcc3-eab6-4984-a852-d7a88af5b082.png)

Try not to work manually in generating points like the above points, that is, generate points with the help of functions so that you can create and test points and groups with distinctive features and shapes every time.
Then classify your fake data with SVM. Test without core, with different types of cores, different parameters for each core, etc.
Plot the line of separators found by the SVM next to the training points on a graph. Preferably, draw the line related to Margin. Common libraries usually provide a function to draw the dividing line and margin.

Part II :
First, you need a database (Set Data (choose for yourself. Preferably choose an image database. For example, as a suggestion, you can use databases related to the identification of English handwritten digits such as USPS2 or MNIST) or if you can find a database for Persian handwritten digits. you did) consider Divide the selected database into two parts, train and test, and perform the training phase on the train set, and then obtain the classification accuracy with SVM in the test data.
