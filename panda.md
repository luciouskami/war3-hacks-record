#Panda全图

##魔兽环境：

war3_ver = 1.27a

inlinepatch:

Game.dll + 0x1BFF01 

Game.dll + 0x1C0053  

Game.dll + 0x1F7C23  

Game.dll + 0x1FB323  

Game.dll + 0x2339B3  

Game.dll + 0x251268   

Game.dll + 0x370A36 

Game.dll + 0x392818  

Game.dll + 0x392858   

Game.dll + 0x3A5835    

Game.dll + 0x3A9940  

Game.dll + 0x3AA9F6 
  
Game.dll + 0x3AAA23  

Game.dll + 0x3B8C42    

Game.dll + 0x3B947A   

Game.dll + 0x3BD7C2    

Game.dll + 0x40BFFB     

Game.dll + 0x47EE5E    

Game.dll + 0x5E179D   

Game.dll + 0x65168B   

Game.dll + 0x651694   

Game.dll + 0x66E44B   

Game.dll + 0x66E71E   

Game.dll + 0x740420  

##线程操作：

判断用户是否选择军团战争选项，如果是则枚举反作弊模块线程并结束。

##行为：

设置1个定时器，用来监视魔兽运行，魔兽运行后向Game.dll写入补丁数据并关闭自身以躲过网易的窗口、控件特征检测。

##网络验证：

可可网络验证V10
