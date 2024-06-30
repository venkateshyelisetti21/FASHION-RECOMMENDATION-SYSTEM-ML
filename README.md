
# Fashion Recommendation system

A fashion recommendation system is a specialized tool designed to suggest clothing and accessories to users based on their preferences, behaviors, and specific inputs. It leverages advanced technologies such as machine learning and neural networks to analyze data and provide personalized recommendations. Unlike traditional systems that rely solely on user purchase history, modern fashion recommendation systems can process various inputs, including images uploaded by users. By analyzing these images, the system identifies patterns, styles, and features, and matches them with similar products in its database.

This innovative approach addresses the common scenario where users see a particular item they like and seek similar products. The system enhances the shopping experience by offering tailored suggestions that align with the user's aesthetic preferences. It helps retailers showcase their full product range, increases user engagement, and ultimately drives sales by making it easier for customers to discover items they will likely enjoy and purchase.


## Intro of the project

Humans are naturally attracted to visually appealing things, which has fueled the growth of the fashion industry over time. With the advent of recommender systems across various domains, the retail sector is increasingly investing in cutting-edge technology to enhance their business. Fashion has been around for centuries and will continue to thrive in the future. Women, in particular, are closely associated with fashion and style, facing a larger array of products which complicates decision-making. Fashion has become a crucial aspect of life for modern families, as a person's attire often influences how they are perceived. Furthermore, apparel providers want their customers to explore their entire product range to find what they truly like, a task that can't be fully accomplished by merely visiting a physical store.


##  Methodology

In this project, we propose a model that uses Convolutional Neural Network and the Nearest 
neighbour backed recommender. As shown in the figure Initially, the neural networks are trained and then 
an inventory is selected for generating recommendations and a database is created for the items in 
inventory. The nearest neighbour’s algorithm is used to find the most relevant products based on the 
input image and recommendations are generated.


## Training

In the fashion recommendation system project, neural networks are employed to process and analyze images of fashion products. Using a dataset like the Fashion Product Images Dataset, the neural network is trained to identify and extract features from the input images. These features are then used to find visually similar items. The training process involves using convolutional neural networks (CNNs) to learn patterns and styles from the images. Once trained, the network can accurately recommend fashion items that closely match the user's input, enhancing the shopping experience by providing personalized and visually appealing suggestions.


## Recommendation generation

To generate recommendations, our proposed approach uses Sklearn Nearest neighbours Oh Yeah. This allows us to find the nearest neighbours for the given input image. The similarity measure used in this Project is the Cosine Similarity measure. The top 5 
recommendations are extracted from the database and their images are displayed.


## Testing and outputs

To address the challenges posed by the limited size of the fashion dataset, we utilize the concept of transfer learning. By pre-training classification models on the extensive DeepFashion dataset, which includes 44,441 garment images, we significantly enhance the model's performance. These pre-trained networks are then fine-tuned using our smaller dataset, ensuring that the model leverages the rich features learned from the larger dataset.

The training and validation processes conducted on the smaller dataset demonstrate remarkable model accuracy. The results indicate low error rates and loss, along with a high F-score, validating the effectiveness of the transfer learning approach. This method ensures robust performance even with a limited dataset, enhancing the overall accuracy and reliability of the fashion recommendation system.

### Dataset Source Link

[Kaggle Dataset size 572 MB]
(https://www.kaggle.com/paramaggarwal/fashion-product-images-small)



## Conclusion

In this project, we have introduced an innovative framework for fashion recommendation, emphasizing data-driven, visually relevant, and simple yet effective recommendation systems for fashion product images. The approach involves a two-stage process that is first, extracting features from an input image using a CNN classifier, allowing customers to upload any fashion image from an e-commerce website; second, generating similar images based on the input's features and texture. This methodology enhances recommendation accuracy and enriches the fashion exploration experience for both direct and indirect consumers. Continued research in this area will further improve recommendation systems, benefiting the fashion industry and its users.
