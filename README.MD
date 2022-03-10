## 使用fasttext进行文本分类
数据使用的是百度ai studio的常规赛，新闻文本分类的数据集。[下载链接](https://aistudio.baidu.com/aistudio/datasetdetail/103654/0)

data_calssical：存放数据的文件夹
>dev.txt：原始验证集；  
devs_data.txt：转换之后符合fasttext的验证集；  
train_data.txt：原始训练集；  
L_data.txt：转换之后符合fasttext的训练集；  
text.txt：测试集（无标签）  

text_classical.ipynb：使用fasttext进行文本分类

测试集的准确率在82%左右。