# VirtureClick
Jul 26, 2020更新记录：

1.增加挂机功能

2.增加小米9和小米5渠道，并适配

3.增加战令更新后的烧绳机制

简述：
自己练手顺便写了一个简单的炉石传说脚本：一键投降+下一局

代码核心主要是两个Service，一个是悬浮窗，一个是虚拟点击。目前悬浮窗只适配了Android 8.0及之后的版本

由于炉石传说游戏不是用java写的，监控不到其界面变化，就拿不到id，所以这里通过模拟点击来实现的，不同手机分辨率不同，坐标会有差异
