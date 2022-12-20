# Search By Images

Reverse image search, or content-based image retrieval also known as image content query and content-based visual information retrieval is the application of computer vision techniques to the problem of image retrieval, that is, the problem of searching for digital images in large databases, and thus the image retrieval system It is a computer system used to browse, search and retrieve images from a large image database
## Data Set
The dataset is from kaggle, a list of more than 27,000 consumer reviews of 65 Amazon products provided by the Datafiniti product database. The dataset includes basic product information, rating, review text, and more for each product. It is a sample of a large data set. Through Datafiniti taken from Amazon.

## project Implementation
Started by using a pretrained model to apply the (feature extraction) step for the images in the data set then save the feature vectors that we got in an array then did the same for the new image then find suitable (similarity measurement) and that apply this idea using KNN to find similar images.
