# 股票龙虎榜打榜研究


## 研究思路：

1、统计不同的abnormal_code的次日收益率的分布（找出哪种abnormal_code更容易持续上涨——可加大盘不同区间段研究） <br>
2、统计次日收益率和net_value、total_value_ratio的关系<br>
3、统计前3（n）日是否也出现龙虎榜对次日收益率是否有显著影响<br>
4、加入一些新的特征（前n日成交量、前n日净流入net_value）,把次日收益率做4分类，拿机器学习模型学习<br>

## 名词解释：
abnormal_code: 异常波动类型（龙虎榜上榜的类型）<br>
net_value:净额(买入金额 - 卖出金额)<br>
total_value：买入卖出金额之和（买入金额+卖出金额）<br>
amount:市场总成交额<br>

## 研究平台：
聚宽（https://www.joinquant.com/view/user/floor?type=mainFloor）<br>

## 策略模拟跟踪：
链接：https://www.joinquant.com/algorithm/live/liveUrlShareIndex?backtestId=fcf87366e23f6b42e7d5f061e160ee4f  密码：lvah7l <br>




