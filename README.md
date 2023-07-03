# Padavan
由keke1023基于hanwckf,chongshengB以及padavanonly的源码整合而来，支持7603/7615/7915的kvr  
编译方法同其他Padavan源码，主要特点如下：  
1.采用padavanonly源码的5.0.4.0无线驱动，支持kvr  
2.添加了chongshengB源码的所有插件  
3.其他部分等同于hanwckf的源码，有少量优化来自immortalwrt的padavan源码                                                                            
4.vb1980持续对代码测试、改进和更新：https://github.com/vb1980/Padavan-KVR.git  
5.添加了MSG1500的7615版本config  
  
以下附上他们四位的源码地址供参考  
https://github.com/hanwckf/rt-n56u  
https://github.com/chongshengB/rt-n56u  
https://github.com/padavanonly/rt-n56u  
https://github.com/immortalwrt/padavan
  
最后编译出的固件对7612无线的支持已知是有问题的，包含7612的机型比如B70是无法正常工作的  
已测试的机型为MSG1500-7615，JCG-Q20，CR660x  
  
固件默认wifi名称
 - 2.4G：机器名_mac地址最后四位，如K2P_9981
 - 5G：机器名_5G_mac地址最后四位，如K2P_5G_9981

wifi密码
 - 1234567890

管理地址
 - 192.168.2.1

管理账号密码
 - admin
 - admin

**最近缝合、更新的代码都来自于以下大佬们的4.4内核代码，缝合4.4多拨（本地不支持多拨，未经测试）及更新、优化其他功能**
- https://github.com/hanwckf/padavan-4.4
- https://github.com/MeIsReallyBa/padavan-4.4
- https://github.com/tsl0922/padavan
- https://github.com/TurBoTse/padavan
- https://github.com/vb1980/padavan-4.4.git
