# 双均线策略回测

## 策略逻辑
- 5日均线上穿20日均线 → 买入
- 5日均线下穿20日均线 → 卖出

## 运行结果
![收益对比图](result.png)

## 使用方法
1. 安装依赖：`pip install tushare pandas matplotlib`
2. 在代码中填入你的 Tushare Token
3. 运行：`python dual_ma_strategy.py`
