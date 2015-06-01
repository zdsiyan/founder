# 互联网创业者 founder
一个跟创业者有关的桌面游戏 A desktop game of founder

# 简要说明

* 翻了几个license感觉太麻烦，决定用MIT
* 有关创业者的游戏规则，将会以文字，图片以及电子表格文件的形式发布在git上
* 可供2-4人玩
* 本页为基础包，后续会编辑扩展包

<hr>

# 材料说明

* 骰子1枚
* 计算器1-4部，可用手机计算器代替
* 2人玩时1幅扑克，3-4人玩时2幅扑克
* A4纸2张用于打印事件牌和地图，也可手绘。

<hr>

# 扑克使用说明
* 扑克分为3个牌堆
   小丑牌为角色牌堆，A-10为员工牌堆，J-K为功能牌堆
* 角色牌堆: 共4个角色
  用笔做记号标明：手游创业，社交创业，电商创业，O2O创业。
   手游创业收入为正常计算的120%。社交创业员工薪资为正常计算的80%。电商创业可在抓取员工牌时多取一张。O2O创业可在抓取功能牌时多取一张。电商和O2O在第一次破产时可获得一次融资机会，需扔骰子5点及以上。融资可获得200万元无息贷款。
  在起始位置，手游同社交可花费200万完成角色互转，电商同O2O可花费200万完成角色互转。
* 员工牌堆
  10 代表运维牌，可阻挡黑客一次破坏，阻挡后进入牌堆。A-9 代表员工牌。数字代表薪资，发薪后由下家抽取一枚进入牌堆。
  J 代表破坏牌，红色代表挖掘机，可挖断对方电缆，使对方资产下降10%，使己方增长10%；黑色代表黑客，可破坏对方网络，使对方资产下降20%，使己方增长20%
  Q 代表增长牌，红色代表收入增长20%，黑色代表收入增长40%。
  K 代表政策牌，红色代表所有人资金增长20%，黑色代表含自己的所有人资金缩水20%
  相同的功能牌可多张同时使用，同时使用时，累加效果为20%+20%，即5张K牌可使所有角色破产。

<hr>

# 规则说明
* 万为基础单位，计算时出现的剩余资金小数部分抹去，非四舍五入
* 初始体力100点，降为0需进入医院休息3回合，休息后体力回复到80
* 2-3人参加时可自由选取角色牌。4人参加时需投掷骰子决定使用哪个角色，将角色牌依次排开，根据点数由左至右，再由左至右选定。出场时需投掷骰子决定初始资金。1-3为融资失败，需要下一轮继续投掷，4-6得出的数字*200万为初始资金
* 获得初始资金后投掷骰子，决定可抓取几张员工牌
* 有员工牌才可以行动，失去全部员工牌既为失败
* 失去全部资金且不可再融资既为失败

<hr>

# 基础地图包
* 起点，再次经过起点可融资
* 机房：
  初始所有角色没有机房，挖掘机将可破坏所有角色，建设机房以后一张挖掘机只能破坏一个机房，但可使机房变为无主状态。玩家路过无主机房时，可选择投资或不投资。
* 事件
  事件牌，抓取随机事件，抓取后立即执行，执行后投入牌堆洗牌3次
* 支付薪水，手头的员工牌点数相加
* 机场，支付5万元可跳转至地图任意机场
* 商店，支付50万购买一张功能牌，从牌堆中抽取，但不受角色技能加持的影响，仅能抽取一张
* 医院，体力降为0则需传送至医院休息，花费50万
* 咖啡馆，体力增长10点，花费10万
* 加班，体力降低5点，花费10万
* 按时上下班，花费10万
* 产品发布，发布过至少一个版本才可以再融资
