1. 下载anaconda安装bash Anaconda3-5.2.0-Linux-x86_64.sh
2. 配置anaconda环境   
 sudo gedit ~/.bashrc
 export PATH="/home/xupp/anaconda3/bin:$PATH"
source ~/.bashrc
3. 创建python3.6的虚拟环境conda create -n python36 python=3.6,激活虚拟环境：conda activate python36，退出虚拟环境 conda deactivate
4. conda install numpy=1.16.4
5. conda install tensorflow=1.14
6. pip install cython matplot pillow
