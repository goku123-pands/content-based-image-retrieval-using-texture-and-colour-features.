# content-based-image-retrieval-using-texture-and-colour-features.
Due to the exponential growth of image data there is a compelling 
need for innovative tools which can easily manage, retrieve and
visualize images from the large multimedia databases. In recent 
years, there are many advanced techniques which have emerged in 
the field of Content-Based Image Retrieval (CBIR).
The main goal of the CBIR is to find images which are similar to 
the query image visually without using any textual descriptions 
for the image. CBIR is the field and collection of technology and 
algorithms, whose detail study enable the user to query image 
databases by using image content such as colour, texture, objects 
and their geometries not by using textual attributes such as image 
name or other keywords. In CBIR various techniques have
been developed over the past few years based on various features 
of images. Among these features, colour is one of the effective 
feature which can express visual information, as well as invariant 
on the complexity. By the use of colour features images can be 
grouped together very easily. Texture analysis is another major 
component of image processing and work as the backbone for 
many applications such as remote sensing, quality inspection, 
medical imaging, etc.
In this project we have demonstrated both colour properties as well as 
texture – spatial properties for image retrieval.


1. Colour based image retrieval.


User has to input a query image – RGB image in JPEG
format.
Based on colour as a feature, we display the best match and a worst 
match from the database, along with a plot showing the measure of 
similarity among all the database images.
We have used the technique of histogram normalization on grayscale 
images to find the measure of colour as a feature in each image and then 
comparison is based on Euclidean distance measurement, which ranks 
the images according to their similarity.


2. Texture based image retrieval.


User has to input a query image – RGB image.
Based on spatial properties – texture using Contrast, Correlation,
Energy and Homogeneity we extract the similar images from the 
database which have been ranked based on the distance calculated from 
the Euclidean measurement.
