# committee
多线程，模拟柜台办理业务

《园区管委会大厅业务系统》

1、园区管委会大厅内有八个服务窗口，其中1-6号为个人业务窗口，
7号为内资企业窗口，8号为外资企业窗口

2、对应客户类型有三种，	1：个人用户 	2：内资企业用户 	3：外资企业用户

3、各客户按其类型到对应窗口依次办理业务

4、异步随机生成客户类型，客户比例为  外资企业：个人用户：内资企业  = 1:6:3

5、生成客户的时间间隔自定，同时对于外资企业用户和内资用户的服务时间有一个最大值和一个最小值，
具体服务时间可以在这个范围内随机生成，而个人用户服务时间为固定值（最小值）

6、当外资企业服务窗口与内资企业窗口没有对应的客户时，可接受个人用户业务，
但如果一但有对应其窗口的客户，则该客户优先  

7、程序结果以日志方式展现
