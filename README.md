# Python Data Science Handbook

# Python数据科学手册

> [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/jakevdp/PythonDataScienceHandbook/master?filepath=notebooks%2FIndex.ipynb)
> [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/Index.ipynb)

[![在线Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/wangyingsm/Python-Data-Science-Handbook/master?filepath=notebooks%2FIndex.ipynb)
[![谷歌Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wangyingsm/Python-Data-Science-Handbook/blob/master/notebooks/Index.ipynb)

**[本书Github免费notebook格式中文翻译目录](notebooks/Index.ipynb)**

**[下载中文版PDF可打印格式](printable/README.md)**

> This repository contains the entire [Python Data Science Handbook](http://shop.oreilly.com/product/0636920034919.do), in the form of (free!) Jupyter notebooks.

本代码仓库包含着整本[Python Data Science Handbook](http://shop.oreilly.com/product/0636920034919.do)书籍，使用免费的Jupyter notebook格式呈现。

译者注：作者英文版[原仓库地址](https://github.com/jakevdp/PythonDataScienceHandbook)。

![cover image](notebooks/figures/PDSH-cover.png)

## How to Use this Book

## 如何阅读本书

> - Read the book in its entirety online at https://jakevdp.github.io/PythonDataScienceHandbook/

> - Run the code using the Jupyter notebooks available in this repository's [notebooks](notebooks) directory.

> - Launch executable versions of these notebooks using [Google Colab](http://colab.research.google.com): [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/Index.ipynb)

> - Launch a live notebook server with these notebooks using [binder](https://beta.mybinder.org/): [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/jakevdp/PythonDataScienceHandbook/master?filepath=notebooks%2FIndex.ipynb)

> - Buy the printed book through [O'Reilly Media](http://shop.oreilly.com/product/0636920034919.do)

- 在线阅读本书（英文原版）：https://jakevdp.github.io/PythonDataScienceHandbook/ 。
- 使用Jupyter notebook运行本仓库的代码，代码在[notebooks](notebooks)目录下。
- 在[谷歌Colab](http://colab.research.google.com): [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wangyingsm/Python-Data-Science-Handbook/blob/master/notebooks/Index.ipynb)上运行这些notebooks。
- 在[在线binder](https://beta.mybinder.org/): [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/wangyingsm/Python-Data-Science-Handbook/master?filepath=notebooks%2FIndex.ipynb)上运行这些notebooks。
- 在[O'Reilly Media](http://shop.oreilly.com/product/0636920034919.do)网站上购买本书（英文原版）纸质版。

## About

## 关于

> The book was written and tested with Python 3.5, though other Python versions (including Python 2.7) should work in nearly all cases.

本书在Python 3.5环境中编写和测试，但其他的Python版本（包括Python 2.7）也应该可以通过绝大部分示例。

> The book introduces the core libraries essential for working with data in Python: particularly [IPython](http://ipython.org), [NumPy](http://numpy.org), [Pandas](http://pandas.pydata.org), [Matplotlib](http://matplotlib.org), [Scikit-Learn](http://scikit-learn.org), and related packages.
Familiarity with Python as a language is assumed; if you need a quick introduction to the language itself, see the free companion project,
[A Whirlwind Tour of Python](https://github.com/jakevdp/WhirlwindTourOfPython): it's a fast-paced introduction to the Python language aimed at researchers and scientists.

本书介绍了在Python中操作数据的核心库：特别包括 [IPython](http://ipython.org), [NumPy](http://numpy.org), [Pandas](http://pandas.pydata.org), [Matplotlib](http://matplotlib.org), [Scikit-Learn](http://scikit-learn.org) 和其他相关的包。预设前提是读者已经熟悉Python语言；如果你需要语言本身的一个快速入门介绍，可以去参考兄弟项目，[A Whirlwind Tour of Python](https://github.com/jakevdp/WhirlwindTourOfPython): 这是一个面向研究人员和科学家的快速Python语言入门介绍。

译者注：[Python旋风之旅](https://github.com/wangyingsm/wwtop)中文翻译已经全部完成。

> See [Index.ipynb](http://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/Index.ipynb) for an index of the notebooks available to accompany the text.

可以参见[目录](notebooks/Index.ipynb)查看所有notebooks的列表。

## Software

## 软件

> The code in the book was tested with Python 3.5, though most (but not all) will also work correctly with Python 2.7 and other older Python versions.

本书的代码在Python 3.5环境中测试通过，但绝大部分情况下，代码都能在Python 2.7和其他更早的版本下正常使用。

译者注：Python2将于2020年1月停止维护，因此强烈不建议继续使用Python2。

> The packages I used to run the code in the book are listed in [requirements.txt](requirements.txt) (Note that some of these exact version numbers may not be available on your platform: you may have to tweak them for your own use).
To install the requirements using [conda](http://conda.pydata.org), run the following at the command-line:

```
$ conda install --file requirements.txt
```

运行本书的代码需要用到的第三方包列在 [requirements.txt](requirements.txt) 文件中（请注意，部分确定版本的包可能并不适用于你的系统：你可能需要根据需要调整它们）。要使用 [conda](http://conda.pydata.org) 安装需要的依赖包，可以执行下面的命令：

```shell
$ conda install --file requirements.txt
```

> To create a stand-alone environment named ``PDSH`` with Python 3.5 and all the required package versions, run the following:

```
$ conda create -n PDSH python=3.5 --file requirements.txt
```

如果需要创建一个独立的Python环境，例如叫`PDSH`，使用Python 3.5环境和安装所需的第三方包，执行下面的命令：

```shell
$ conda create -n PDSH python=3.5 --file requirements.txt
```

> You can read more about using conda environments in the [Managing Environments](http://conda.pydata.org/docs/using/envs.html) section of the conda documentation.

可以参见conda文档的[管理Python环境](http://conda.pydata.org/docs/using/envs.html)章节了解更多的内容。

## License

## 协议

### Code

### 代码

不翻译了，[MIT license](LICENSE-CODE)。

> The code in this repository, including all code samples in the notebooks listed above, is released under the [MIT license](LICENSE-CODE). Read more at the [Open Source Initiative](https://opensource.org/licenses/MIT).

### Text

### 文字

不翻译了，[CC-BY-NC-ND license](LICENSE-TEXT)。

> The text content of the book is released under the [CC-BY-NC-ND license](LICENSE-TEXT). Read more at [Creative Commons](https://creativecommons.org/licenses/by-nc-nd/3.0/us/legalcode).
