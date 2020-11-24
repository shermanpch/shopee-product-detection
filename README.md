# Shopee Code League - Product Detection

## Background
At Shopee, we always strive to ensure the correct listing and categorization of products. For example due to the recent pandemic situation, face masks become extremely popular for both buyers and sellers, everyday we need to categorize and update a huge number of masks items. A robust product detection system will significantly improve the listing and categorization efficiency. But in the industrial field the data is always much more complicated and there exists mis-labelled images, complex background images and low resolution images, etc. The noisy and imbalanced data and multiple categories make this problem still challenging in the modern computer vision field.

## Task
In this competition, a multiple image classification model needs to be built. There are ~100k images within 42 different categories, including essential medical tools like masks, protective suits and thermometers, home & living products like air-conditioner and fashion products like T-shirts, rings, etc. For the data security purpose the category names will be desensitized. The evaluation metrics is top-1 accuracy.

## Sample Dataset
<kbd><img src="/sample_data/sample_1.jpg" width="250"></kbd><kbd><img src="/sample_data/sample_4.jpg" width="250"></kbd><kbd><img src="/sample_data/sample_5.jpg" width="250"></kbd>
<kbd><img src="/sample_data/sample_2.jpg" width="250"></kbd><kbd><img src="/sample_data/sample_6.jpg" width="250"></kbd><kbd><img src="/sample_data/sample_7.jpg" width="250"></kbd>
<kbd><img src="/sample_data/sample_3.jpg" width="250"></kbd><kbd><img src="/sample_data/sample_8.jpg" width="250"><kbd></kbd><img src="/sample_data/sample_9.jpg" width="250"></kbd>

## Evaluation Metric
Categorization Accuracy

## Results
|Public Leaderboard|Private Leaderboard|
|:---|:---|
|0.81235|0.82124|

## Reference
**Jupyter Notebook**
<br>
https://github.com/shermanpch/shopee-product-detection/blob/main/EfficientNetB4.ipynb

**Shopee Code League - Sentiment Analysis**
<br>
https://www.kaggle.com/c/shopee-product-detection-open
