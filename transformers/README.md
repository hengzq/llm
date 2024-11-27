


### 安装Python环境

```shell
conda create -n p310 python= 3.10.14

# 激活环境
conda activate p310
```


### 安装 Python 依赖软件包

完整 Python 依赖软件包见[requirements.txt](requirements.txt)。

```shell
pip install -r requirements.txt
```


### 安装和配置 Jupyter Lab


```shell
conda install -c conda-forge jupyterlab
```

启动
```shell
jupyter lab
```