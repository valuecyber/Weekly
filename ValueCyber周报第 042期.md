**VCT进度周报**

第四十二期：2019.03.25—03.31

#### **1. 研发Development** 

1. VCT进行共识和通信部分的优化，为生产网络的开发部署做准备。
   * 根据新共识框架，引入一个新库:txdb，在txdb中加入TxsCF，GlobalCF和PersistCF； 简化之前旧库db里blockCF,并移动部分数据到txdb里。
   * 完成基于Gossip协议的事务网络(使用scuttlebutt模型实现)的设计与编码
   * 完成peer grpc通信模块的重构。将不同类型的grpc消息放在不同的grpc service里。从而提高消息throughput和代码复用率。

#### **2. 市场Market**

VCT可通过Bit-Z、FCoin 两个交易所进行交易: 

全球市场排名（CMC）：669名

**流通市值**:  

$2,585,128 USD 
626 BTC 
18,154 ETH

**近24小时成交量** : 

$723,680 USD 
175.38 BTC 
5,082 ETH

**流通量**: 107,837,023 VCT

**数据来源：**https://coinmarketcap.com/currencies/valuecybertoken/

**数据统计时间:** 2019年 4月8日12：00

#### **3. 动态&运营 Dynamic和Operation**

1.     在社区建设中，计划组织力量，增加与VCT志同道合的伙伴，将 VCT的理念、思想传播出去。该计划将在技术应用开发、生产网络构建上做为重要建设方向。
2.    积极探索VCT在生产网络上的多种应用场景，目前电商、众筹和供应链为主要探索方向。

#### **4. 人才招聘（推荐有奖）Recruitmen**

**1.职位名称 : 高级前端开发工程师-react**

**岗位职责：**

1. 前端组件的设计与实现，相关框架的定制与修改及优化；

2. 负责产品的前端复杂交互的开发及项目中复杂问题攻克；

3. 提升前端团队开发能力。

**任职资格:**

1.      本科以上学历，计算机相关专业与三年以上互联网从业经验及二年以上React开发经验，能力优秀者无限制；

2.      熟悉基本的计算机网络概念，熟悉HTTP协议，并能够灵活使用；熟悉各种Web标准规范, 熟练掌握HTML、CSS以及HTML5、CSS3，对表现与数据分离、Web语义化有深入了解；

3.      熟练运用ES5、ES6、ES7语法，了解基于JS的面向对象思想及模块化开发，熟悉BOM、DOM，熟悉TypeScript者优先；

4.      精通React相关技术栈，掌握redux、react-redux、react-router、redux-form；

5.      熟悉前端项目部署及发布，对Grunt、Webpack有一定了解, 对前端工程化有研究者优先；

6.      有使用Ant Design、Bootstrap、Element等组件库经验；

7.      有责任心，三观端正，对技术有热情，能融入团队建立良好人际关系, 有一定的技术领导力。

以下为加分项:

- 熟悉NodeJS，有Express类Web应用开发框架使用经验，具备后端开发能力或经验；

- 对数据结构及算法有深入理解；

- 对常用框架源代码、原理有深入研究；

- 熟悉Vue相关框架

 

**2.职位名称 : 产品经理**

**职位描述：**

1. 负责区块链相关产品；

2. 使用设计工具完成产品设计、交互设计和原型设计，并输入相关文档；

3. 负责产品设计、开发、测试、上线、迭代的全流程项目管理；

4. 参与产品的运营和推广；

**岗位要求：**

1. 对新事物有强烈的好奇心、探索欲；

2. 处女座般极致的的完美主义者；

3. 拥有强大的逻辑思维能力和分析能力；

4. 出色的学习能力和沟通能力；

5. 掌握必要的产品设计方法和工具；

**欢迎大家积极推荐优秀人才，成功入职后，我们给予推荐人的VCT奖励标准如下：*10000 VCT，连续工作满六个月加送10000 VCT**