# 临床机器学习教学

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/oranges7/clinical-ml-teaching/main)

本项目为临床研究人员提供Python和机器学习的入门教学。

## 课程内容

### 1. Python基础培训
- 变量和数据类型
- 数据结构（列表、字典）
- 控制流（条件判断、循环）
- 函数定义和使用
- NumPy数值计算
- Pandas数据处理
- Matplotlib数据可视化

### 2. 临床机器学习示范
- 模拟临床数据生成
- 数据探索性分析（EDA）
- 数据预处理和特征工程
- 机器学习模型训练（逻辑回归、随机森林）
- 模型评估和解释
- 特征重要性分析

## 快速开始

### 在线运行（推荐）

点击上方的Binder徽标，即可在浏览器中直接运行所有教程，无需安装任何软件。

### 本地运行

1. 克隆仓库：
```bash
git clone https://github.com/oranges7/clinical-ml-teaching.git
cd clinical-ml-teaching
```

2. 创建虚拟环境并安装依赖：
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
# 或
venv\Scripts\activate  # Windows

pip install -r requirements.txt
```

3. 启动Jupyter Notebook：
```bash
jupyter notebook
```

4. 在浏览器中打开相应的notebook文件。

## 文件说明

| 文件 | 说明 |
|------|------|
| `01_python_basics.ipynb` | Python基础培训教程 |
| `02_clinical_ml_demo.ipynb` | 临床机器学习示范教程 |
| `requirements.txt` | Python依赖包列表 |
| `runtime.txt` | Binder Python运行时版本 |
| `.gitignore` | Git忽略文件配置 |

## 学习路径

建议按照以下顺序学习：

1. **Python基础培训** → 掌握Python编程基础
2. **临床机器学习示范** → 学习机器学习在临床中的应用

## 注意事项

- 本教程使用模拟数据，仅供教学演示
- 实际临床应用需要使用真实数据并进行充分验证
- 模型预测结果仅供参考，不能替代专业医疗判断

## 许可证

MIT License