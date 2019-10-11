# 中国期货高频数据-民间资源 future_highFreq


　　本项目是一个简单、免费且容易使用的绿色客户端软件，其唯一功能就是为用户提供中国期货市场的高频数据，包括1min的K线和0.5秒的tick快照两种数据。本软件的用户群体主要是在国内期货市场做交易的私募基金研究员、民间投资者、在校学生，尤其是对期货（或股票）高频数据接触时间少于1年的投资者。
	
　　本项目的数据并非交易所官方第一手来源，故严谨性有所欠缺，专业的机构投资者应该选用更专业、更正规的高频数据资源。但是，正规高频数据的费用往往不是个人投资者愿意去支付的，因此本项目在永久免费使用的前提下，希望为广大普通投资者提供相对比较准确、全面的期货高频数据资源。
	
　　本项目所有数据都来自于天软科技和掘金量化３，特此感谢！


## 环境准备
* 支持 windows7 和 windows10 系统，其他 windows 系统未做测试，暂不支持 linux

## 安装步骤
* 绿色软件无需安装，下载好zip文件后解压，里面的 future_highFreq.exe 可以直接使用 
* 这里的源代码仅供参考，可以用Qt Creator编译

## 使用方法
![image](https://github.com/irontowersh/future_highFreq/blob/master/images/mainWindow_1.png)
1. 打开软件exe后，链接服务器，正常情况下等待几秒后即可连上。
2. 已经连好服务器后，选择数据的频率，并查询期货合约列表，等待几秒后即出现结果。
3. 左侧树状图中，可以双击选择想要下载的具体某一张合约。
4. 选择查询时间段（tick数据长度建议不超过1个月），然后开始下载。经过漫长的时间，或者手动中途停止，数据结果会出现在中央的表格中。
5. 查看到表格数据是自己想要的结果，就可以在右上角导出csv文件到本地。之后，也可以开始下一次的数据查询操作。
6. 右侧区域中，是一些简单的数据统计，和频数直方分布图。
7. 中间的分割线可以被左右拖动。

## 数据来源
* 数据最早开始于2010年1月1日，更早年的期货数据是空缺的。最新的数据会不断地在周末更新，但是会有2周左右的滞后，查询最近一个月的数据会有查询不到的情况。
![image](https://github.com/irontowersh/future_highFreq/blob/master/images/logo.ico)
* 2010年到2019年6月底的1min和tick数据都来源于天软科技
* 传送门：http://www.tinysoft.com.cn(http://www.tinysoft.com.cn)
![image](https://github.com/irontowersh/future_highFreq/blob/master/images/logo.ico)
* 2019年7月初以后的1min和tick数据都来源于掘金量化3
* 传送门：https://www.myquant.cn(https://www.myquant.cn)

