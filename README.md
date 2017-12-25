# Emotion-Recognition-using-Python
## 链接复制于https://github.com/NarendrenSaravanan/Emotion-Recognition-using-Python
````
cd Emotion-Recognition-using-Python/
````
# 运行步骤如下
````
virtualenv env   创建虚拟环境
brew tap homebrew/science
brew install opencv  安装opencv
````

## 安装完成之后，按照提示进行以下两个命令
````
mkdir -p /Users/lulifei/Library/Python/2.7/lib/python/site-packages
echo 'import site; site.addsitedir("/usr/local/lib/python2.7/site-packages")' >> /Users/lulifei/Library/Python/2.7/lib/python/site-packages/homebrew.pth
````
完成上面的操作之后命令行输入python，输入以下命令，验证是否安装成功
````
import cv;import cv2
````

## 安装以下的依赖
````
pip install imutils
````
````
sudo pip install pygame
````
````
brew install cmake
brew install boost
brew install boost-python --with-python3
pip install dlib
````

## 运行python文件
````
python emotion recognition.py 
````

以上即可正常运行
