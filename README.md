# 系统调用序列数据集
该系统调用序列数据集基于Ubuntu18.04采集，包含攻击和正常两种类别的主机系统调用序数据，其中正常类别数据从正常提供服务的系统中采集，异常数据是使用Metasploit渗透测试框架利用相应的软件漏洞进行相关数据的采集。结构如下：

    FL_HIDS/
      attack/
        Cryptomining/
        Linux 提权攻击/
        MySQL/
        Nginx/
        Redis/
        口令猜测/
      normal/
        FTP/
        Kafka/
        MySQL/
        Nginx/
        Redis/
        SSH/   
