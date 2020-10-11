# NWPU-Exam-Template
![](https://img.shields.io/badge/TeX-template-yellow.svg) ![](https://img.shields.io/badge/license-GNU%20GPL%20v3.0-blue.svg) ![](https://img.shields.io/badge/status-complete-brightgreen.svg) 

### 模版说明

This is an **unofficial**  LaTeX template of NWPU Exam for Undergraduates. 

本模版是依据西北工业大学本科生试卷模版 word 版本(2015版) 制作的**非官方** LaTeX 模版，**未经教务处认证**。

本模版在MacTeX 2020下编译通过，不保证其他环境编译通过。需要者可自行下载修改测试。

本模版适用于**数学公式较多**的**非密封**试卷。

### 使用方法

直接在tex源文件修改，具体细节参考tex源文件注释。

#### 主要用到的宏包

| 宏包名                                            | 用处                                            |
| ------------------------------------------------- | ----------------------------------------------- |
| calc                                              | 计算表格列宽                                    |
| ctex                                              | 中文支持                                        |
| enumitem                                          | 用于列表环境                                    |
| environ                                           | 定义新环境：定义试题正文环境 `exam`设置页眉页脚 |
| footmisc                                          | 设置脚注                                        |
| geometry                                          | 设置页面格式                                    |
| makecell, interfaces-makecell, multirow, multicol | 表格相关                                        |
| lastpage                                          | 计算脚注中的总页数；可能需要**编译至少2次**     |
| lipsum                                            | 随机文本，测试用；非必须，可自行去除            |
| tcolorbox                                         | 带框页面宏包，可自动分页，用于定义试题正文框架  |
| tikz                                              | 绘制 `诚信保证` 虚线框                          |
| ulem                                              | 绘制课程信息下划线                              |

### 注意事项、常见问题及解决方法

- 大题数目建议**不超过10**，否则题号得分表格需要重新调整
- <u>源文件打开乱码</u>：本文档采用 `UTF-8` 编码，请选择该编码打开源文件
- <u>宏包缺失</u>：推荐安装最新 `TeXLive 2020` （完全安装）并升级到最新版本。
- <u>编译后不出现中文</u>：用 `xelatex` 编译，**不要用** `pdflatex`
- <u>脚注 `共?页` 不出现总页数</u>：编译至少**2次**

业余时间制作，如有其他编译问题，请自行上网搜索。欢迎反馈 chenhang86@nwpu.edu.cn，但不保证回复。

### License

GNU General Public License v3.0

