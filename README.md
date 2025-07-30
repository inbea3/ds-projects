# 员工情绪分析项目

## 一、项目概述  
本项目通过自然语言处理（NLP）和统计分析，对员工留言进行情感标注、趋势挖掘，并识别离职风险员工，最终构建预测模型分析情绪变化规律，为企业员工管理提供数据支撑。  


## 二、安装说明  
### 1. 依赖环境  
确保已安装 Python 3.8+，并通过以下命令安装依赖：  
```bash
pip install pandas numpy matplotlib seaborn scikit-learn transformers textblob
```


## 三、项目结构
```plaintext
├── data/                  # 数据目录
│   ├── test.csv          # 原始数据
│   ├── test_sentiment.csv# 情感标注后数据
│   └── test_monthly_score.csv # 月度评分数据
├── notebooks/             # 分析 notebooks
│   ├── sentiment_analysis.ipynb # 任务1：情感标注
│   ├── eda.ipynb          # 任务2：EDA
│   ├── score_and_ranking.ipynb # 任务3-4：评分与排名
│   ├── flight_risk.ipynb  # 任务5：离职风险
│   └── predictive_model.ipynb # 任务6：预测模型
├── visualization/         # 可视化输出
│   ├── sentiment_distribution.png # 情感分布
│   └── monthly_trend.png  # 月度趋势
├── README.md              # 本说明文件
└── .env.example           # 环境变量示例（可选）
```
