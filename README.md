# Facial-Generation

之前一个课程作业搞得人脸生成，传到github上记录一下。

**使用的数据集是img_align_celeba，具体下载方法可以百度一下。然后放在和work.ipynb同一目录下**

导出python环境指令：

conda env export > environment.yaml

创建python环境指令：

conda env create -f environment.yaml

如有侵权，请联系我删除。

Conv2d输出尺寸计算公式 输出尺寸 = (输入尺寸 + 2*填充 - 卷积核大小) / 步长 + 1，除法是向下取整