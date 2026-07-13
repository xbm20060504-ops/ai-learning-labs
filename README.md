# AI Learning Labs：李宏毅路线前 6 周补强

这是一套可独立公开、从零运行的原创教学 Notebook，用于补齐进入李宏毅 **Machine Learning 2022** 前后的 Python、NumPy、PyTorch、回归与分类基础。

## 内容

| 周次 | Notebook | 主要成果 |
|---|---|---|
| 1 | `week-01-python-foundations.ipynb` | 列表、循环、函数、`return`、`append`、`even_mean` |
| 2 | `week-02-numpy-pytorch-basics.ipynb` | shape、广播、`@`、Dataset、DataLoader、训练循环 |
| 3 | `week-03-deep-learning-intro.ipynb` | logits、逻辑回归、损失、反向传播 |
| 4 | `week-04-regression-workflow.ipynb` | 原创回归任务、划分、标准化、基线与验证 |
| 5 | `week-05-optimization-classification.ipynb` | Adam、非线性分类、过拟合诊断与正则化 |
| 6 | `week-06-classification-capstone.ipynb` | 三分类综合实践、混淆矩阵、错误分析与累计测试 |

## 使用方法

1. 推荐在 Google Colab 打开 Notebook。
2. 按顺序从上到下运行。
3. 每道练习先在纸上预测或独立编写，再查看参考实现。
4. 只有末尾的 `assert` 自动测试全部通过，才算完成。
5. 每周记录一次：首次正确率、重复错误、代码运行证据和下一步。

本地运行需 Python 3.10+，并使用你已有的 Jupyter 或 VS Code Notebook 环境：

```bash
python -m pip install -r requirements.txt
```

第 1 周只使用 Python 标准库；第 2–6 周使用 NumPy 和 PyTorch。Google Colab 通常已预装这两个包。

## 与主课程的边界

- 主课程：[李宏毅 Machine Learning 2022 官方课程页](https://speech.ee.ntu.edu.tw/~hylee/ml/2022-spring.php)
- 官方作业：[ML2022-Spring 仓库](https://github.com/virginiakm1988/ML2022-Spring)
- 本仓库只提供原创补强示例、合成数据和自动测试。
- 本仓库不复制、改写或重新发布官方课程作业、数据集、讲义，也不包含任何私人 Obsidian 内容、学习答案或成绩。

## 许可

本仓库原创内容采用 MIT License。外部课程材料仍归各自权利人所有。
