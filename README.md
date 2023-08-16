# 对比两种方法的效果

### first-order-model:

我使用的环境是python3.8

新开一个环境，安装所需的依赖：

进入first-order-model,执行`pip install -r requirements.txt`

之后安装面部识别包face_alignment：

```powershell
git clone https://github.com/1adrianb/face-alignment
cd face-alignment
pip install -r requirements.txt
python setup.py install
```

执行：

`python crop-video.py --inp video.mp4`

代码默认使用gpu版本的pytorch, 可能需要重新下载, 或者在命令行参数中修改为cpu版本：

`python crop-video.py --inp video.mp4 --cpu`



裁剪后的结果输出为crop.mp4


