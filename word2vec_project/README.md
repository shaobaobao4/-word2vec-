# Word2Vec 词向量训练与可视化项目

## 项目简介
本项目演示了如何使用 Python 和 Gensim 库训练 Word2Vec 词向量模型。项目包含从文本预处理、模型训练到结果可视化的完整流程。最终通过 t-SNE 算法将高维词向量降维至 2D 平面，直观展示 10 个特定词语的语义分布关系。

## 功能特点
- 使用 CBOW 或 Skip-gram 架构训练词向量。
- 支持自定义语料数据。
- 自动保存训练好的模型 (`*.model`)。
- 生成词向量分布散点图，展示词语间的相似度。

## 环境要求
- Python 3.8+
- 见 `requirements.txt`

word2vec_project/
│
├── README.md              # 项目说明文档
├── requirements.txt       # 项目依赖库
├── data/
│   └── corpus.txt         # 训练语料数据（示例数据）
├── src/
│   ├── train.py           # 训练脚本
│   └── visualize.py       # 可视化脚本（生成图片）
└── models/
    └── word2vec.model     # (运行后生成) 训练好的模型文件
    
## 快速开始

### 1. 安装依赖
```bash
pip install -r requirements.txt
