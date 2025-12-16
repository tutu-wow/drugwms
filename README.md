# drugwms
药品仓管系统 仓库管理系统 计算机毕业设计

 所有源码均本人开发，项目是前后端分离的，所有的项目都具备了完整的业务逻辑，不仅仅局限于基础的增删改查（CRUD）操作，系统亮点众多。

本文注重于计算机毕业设计选题指导，列出题目均有源码， 大家可以去【公众号】(毕业终点站)获取或者加我【qq】(2112698948)提意见(别忘记Star哟)。备注：git

声明：仅用于学习使用，请勿用于任何商业行为！

1.系统非商用，非开源，非无偿。

2.由本人开发，如需源码，请联系以下方式，qq:2112698948。

3.项目有很多，并未全部上传，如果未找到想要的，可直接咨询。

<font style="color:rgb(17, 124, 238);">🎈</font><font style="color:rgb(17, 124, 238);">系统亮点：ARIMA预测、redis缓存、摄像头、扫描二维码、Echarts图形化分析；</font>

# <font style="color:rgb(72, 179, 120);">一.系统开发工具与环境搭建</font>
## <font style="color:rgb(38, 38, 38);">1.系统设计开发工具</font>
<font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">后端使用Java编程语言的Spring boot框架</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">项目架构：B/S架构</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">运行环境：win10/win11、jdk17</font>

<font style="color:rgb(38, 38, 38);"></font>



<font style="color:rgb(38, 38, 38);"></font><font style="color:rgb(72, 179, 120);">前端：</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">技术：框架Vue.js；UI库：ElementUI；   
</font><font style="color:rgb(38, 38, 38);">开发工具：Visual Studio Code；</font>

---

<font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(72, 179, 120);">后端:</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">技术：Java语言、mybatis plus、Spring boot框架；   
</font><font style="color:rgb(38, 38, 38);">开发工具：IDEA 2024版本；</font>

---

<font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(72, 179, 120);">数据库：</font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">数据库：mysql5.7/8.0 </font><font style="color:rgb(38, 38, 38);">  
</font><font style="color:rgb(38, 38, 38);">数据库工具：Navicat12版本；</font>

---

# <font style="color:rgb(72, 179, 120);">二.系统实现（部分截图）</font>
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1765878185739-6700f6ad-fd7a-4354-bb58-ad1a9f08fcc8.png)

## 2.1 仓管管理员
### 2.1.1 药品列表
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1765878198309-387a85db-6cf9-4c85-8944-14533f1b1cd1.png)

### 2.1.2仓库管理
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1765878200831-5d76e699-5a08-413b-9397-d80c2d98ac42.png)

### 2.1.3库位管理
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1765878203213-034b4cd0-8970-4445-aaa3-e17ce99c9b92.png)

### 2.1.4仓库统计
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1765878208011-8e02f5e4-87f5-4b7c-a1e9-eee79003357d.png)

### 2.1.5库位库存可视化
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1765878210226-e495c89c-5be9-4fb6-a37e-30df67d0dee5.png)

### 2.1.6临近过期预警![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1765878212692-59d249ff-1b30-4d5a-b23d-9dc1452e2a32.png)
### 2.1.7补货计划
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1765878215238-1b8fdeb9-9a00-4097-8d3b-dc58dde2d36e.png)

### 2.1.8ARIMA预测
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1765878217494-96f14044-e4e0-4918-be3a-61a9ebcc1db2.png)

### 2.1.9 盘点管理
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1765878219939-3dfba31d-7955-4e29-87c3-8f8ab0a18376.png)

### 2.1.10移库管理
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1765878222254-c789965e-d46f-4bc1-b332-c7858082fe15.png)

### 2.1.11库存记录
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1765878224721-c47ad95c-aea9-4b4e-8c6a-fd0774f3ba04.png)

### 2.1.12库存流水
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1765878226961-b0c5de5d-7722-4f36-8947-ac006f547d8b.png)

### 2.1.13入库单
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1765878230331-5690d2e3-d702-4a18-93b0-ed3393973f4e.png)

### 2.1.14开始入库
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1765878232471-9d6a75a2-dc0f-4578-8572-7dacf6ddfb77.png)

### 2.1.15出库单
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1765878234721-e1338ede-8d79-4fc4-8259-d691cca97be9.png)

### 2.1.16出库单分配明细
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1765878236885-927a3a98-e1df-4e5e-825e-c00676434554.png)

### 2.1.17拣货单
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1765878239594-7a60d859-386f-4353-9192-bdafb883e256.png)

## 2.2 管理员
### 2.2.1 仓管管理员
### ![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1765878241908-e6d6d90a-113b-45e4-ac83-5c83086dbf30.png)2.2.2 供应商管理
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1765878244232-afa404d7-a771-4d0a-8a59-52856f875694.png)

# <font style="color:rgb(72, 179, 120);">三.系统代码结构截图</font>
## <font style="color:rgb(38, 38, 38);">3.1 前端</font>
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1765878247531-72f8b60c-a7f5-4a81-95bc-84c5608d511b.png)

## <font style="color:rgb(38, 38, 38);">3.2 后端</font>
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1765878250470-5808f074-8c1d-4b18-9ff1-5b7ac2c99fc1.png)

## <font style="color:rgb(38, 38, 38);">3.3 数据库</font>
![](https://cdn.nlark.com/yuque/0/2025/png/45326128/1765878252405-b9e79d10-e3c8-4f66-bbad-37683333e09a.png)

# <font style="color:rgb(72, 179, 120);">四.</font><font style="color:rgb(26, 173, 25);">源码获取</font>
<font style="color:rgb(0, 0, 0);">1.原创系统非商用，非开源，非无偿。</font>

<font style="color:rgb(0, 0, 0);">2.项目有很多，并未全部上传，如果未找到想要的，可直接咨询。</font>





