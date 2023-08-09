### 虚拟环境
为文件增加虚拟环境
    1. ```python -m venv .venv```
    2. ctrl + shift + p 弹出命令面板， 如下图所示输入 Python：Select，会弹出下拉选项，选择下图圈出的选项，接下来vscode会显示出当前主机上python环境，，然后选择我们刚才创建的虚拟环境
    通常是./.venv/Script/python.exe
    3. ```.venv\Scripts\activate```
保存虚拟环境
    ```pip freeze > ./.venv/requirements.txt```
下载虚拟环境
    ```pip install -r ./.venv/requirements.txt```

### 其他
- （我需要把虚拟环境下下来吗？）
- 如果ipynb不能顺利运行，可以到colab中使用和测试