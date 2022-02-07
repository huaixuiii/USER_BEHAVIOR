# USER_BEHAVIOR
淘宝用户行为分析


项目适用人群：数据分析方向/运营方向小白（代码尽可能添加了注释）


数据来源：2014年淘宝APP数据-天池
https://link.zhihu.com/?target=https%3A//tianchi.aliyun.com/dataset/dataDetail%3FdataId%3D46%26userId%3D1


IN:
import pandas as pd
import numpy as py
import matplotlib.pyplot as plt
import seaborn as sns
import re

data_user=pd.read_csv(r'C:\data\tianchi_mobile_recommend_train_user.csv')  #导入csv格式文件

