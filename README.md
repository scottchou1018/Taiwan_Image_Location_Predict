# Taiwan_Image_Location_Predict
This is the code for Taiwan Image Location Prediction
## Target
Trying to use the data from google-street-view in taiwan as a dataset to train an model, which can predict where the region that the image is taken.
there are total of 19 region in Taiwan, including:  
[Keelung_City, Taipei_City, New_Taipei_City, Taoyuan_City, Hsinchu_City, Hsinchu_County, Miaoli_County, Taichung_City, Changhua_County, Nantou_County, Yunlin_County, Chiayi_City, Chiayi_County, Tainan_City, Kaohsiung_City, Pingtung_County, Taitung_County, Hualien_County, Yilan_County]
## Dataset
https://github.com/yyh-603/google-street-view-dataset
## Model
### K-means
use K-means as an unsupervised learning approach of this problem.
### Random Forest
use Random Forest as a supervised learning approach of this problem. Testing the influence of the hyperparameters. 
### ResNet
use pretrained ResNet as a deep learning approach of this problem. Testing different number of layers of ResNet including ResNet18, ResNet34, ResNet50, ResNet101, ResNet152.
