# trafficanalysis

        It is a Server traffic statistical system.

         Author: justzx2011@gmail.com  @justzx
        

#Dependencies:
        
#Installation
        1 Download programme
         git clone https://github.com/justzx2011/openyoudao.git
        2 Install iptables 
         apt-get install iptables
        3 config iptables filter 
         # chmod u+x ip.sh
         #./ip.sh
        4 running programme
         #chmod u+x iptables.sh
         $ ./iptables.sh 
        5 config your http server and setting DocumentRoot at /srv/http/traffic
        6 open the url http://localhost/traffic/index.html
TODO
--------------
        2012-6-16   -------   完善README.md
DONE
-----  
        2012-6-16   -------   设计了网页的样式，增加了js特效
        2012-6-15   -------   完成了服务端流量统计脚本的编写，重定向输出到html文件
UPDATES
--------------
        2012-6-16   -------   将项目命名为trafficanalysis，并放置到github上
        2012-6-15   -------   完善了界面设计
RULES
----
        1 桌面版程序，界面上永远不许有按钮
        2 主程序中既是测试程序，不许有功能模块
        3 所有功能模块保持最大化的独立，尤其是界面和程序不许纠缠


Path & File
----
<p>
├── ip.sh
└── README
</p>

Construction
----
