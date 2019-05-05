# MemorizeChineseAncientProses（熟背古文一千遍）
这个简陋的 Python 脚本可以帮助你背古文。

## 使用前准备
1. 确保 Python（最好是 Python 3）已安装。
2. 确保 NumPy 包已安装。
（具体的安装方法很简单，请参考网络上的其他资料）
3. （建议）安装 Visual Studio Code 和 Python 插件，以方便编辑、运行、查看脚本和输入输出文件。

## 如何使用
1. 在脚本所在的目录下新建一个名为`input.txt`的文件，并在文件中写入你想要背的古文。
2. 编辑脚本，调整参数（具体见脚本中的注释）。
3. 运行脚本，这将会在脚本所在的目录下新建一个名为`output.txt`的文件，你可以借助这个文件中的内容来背诵。

## 原理
随机去掉一些文字，帮助你在借助少量提示文字的情况下进行初步背诵，以加速记忆过程。（类似于做填空题）

## 小技巧
1. 大多数古文原文可以在[百度汉语](https://imedwz.baidu.com/t/ipt/Z3iueq)中找到。不建议使用古诗文网提供的原文，因为原文中可能会掺杂了其他内容，排版也不尽人意。
2. 该脚本可以用于娱乐用途，具体方法请自己探索。

## 适用场景
1. 在嘈杂的地方利用碎片时间背古文（例如在地铁上背书）。
2. 古文的逻辑、语法、字词等组成部分过于复杂，难以理解性背诵。
3. 古文中有易错、易漏、易混淆等需要特别注意的部分，可以用`*`包围这部分内容，以作强调（因为`*`会被当做标点符号处理）。
