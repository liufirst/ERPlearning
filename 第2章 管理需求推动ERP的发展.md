<a name="wMyJ3"></a>
## 2.1早期库存管理引发的的订货点法

---



**订货点=单位时区的需求量x订货提前期+安全库存量**
<a name="PKFRp"></a>
## 
<a name="yW4Sv"></a>
## 2.2复杂物料需求带来的时段式MRP

---

<a name="vOFlt"></a>
### 2.2.1订货点法与时段式MRP的区别
![](https://cdn.nlark.com/yuque/0/2023/jpeg/35432257/1678760669943-d0aee601-d818-486f-bac9-8acc0e66664f.jpeg)
<a name="N5h2d"></a>
#### **物料的库存状态：**
<a name="T8u4p"></a>
### 库存+已订货量 — 需求量=可供货量
<a name="iY9dO"></a>
#### 时段式MRP系统的前提条件：

- 每项物料都有一个单独的物料代码
- 有一个主生产计划，它所考虑的时间范围称之**计划展望期**≥产品的累计提前期
- BOM（物料清单）
- 完成的库存记录
<a name="lfEwc"></a>
#### 时段式MRP系统的假设：

- 数据准确完整
- 所有物料订货提前期已知
- 所有物料的出入库都有记录
- 构成父项的所有子项都必须在父项订单下达时到齐
- 物料的消耗是离散的

<a name="hKyg7"></a>
## 2.3物料与生产管理集成的闭环

---

**闭环的理解两层含义：**

- 把能力需求计划（CRP）、车间作业计划、采购作业计划和MRP集成起来，实现一个**物料计划系统**。
- 竭力降低信息的偏差，保证计划的准确执行。通过车间、供应商、计划人员的实时反馈，对计划进行调整和平衡。

**工作过程就是：**<br />**计划——实施——评价——反馈——计划**

![1678846220616.png](https://cdn.nlark.com/yuque/0/2023/png/35432257/1678846230633-f7cbeb07-289f-4079-8f79-1b8a8cade604.png#averageHue=%23f5f5f5&clientId=u6ed5f894-0e39-4&from=paste&height=376&id=ubeae2ece&name=1678846220616.png&originHeight=470&originWidth=443&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=93643&status=done&style=none&taskId=u74b2e057-2d6d-406d-8647-6ea25a91745&title=&width=354.4)
<a name="O7O6C"></a>
## 2.4生产与财务管理一体化的MRP II

---

在已经实现MRP的部门里自然想要更进一步，将资金流也并入到系统中，使的生产计划的各个子系统得到统一。

**MRP II 的特点：**

- **把企业中得各个子系统联系起来，生产和财务两个子系统关系尤为密切。**
- **MRP II 所有的数据来源于企业的中央数据库，各子系统在统一的数据环境下工作。**
- **MRP II 具有模拟功能，是企业高层领导的决策工具。**

<br />

---

<a name="qoLKJ"></a>
## **思考题**
![c3841931499707584ee26d1ea58dd34.png](https://cdn.nlark.com/yuque/0/2023/png/35432257/1678848102562-62de629a-a6ae-4d04-a1eb-13b542a9b626.png#averageHue=%23f5f5f5&clientId=u6ed5f894-0e39-4&from=paste&height=384&id=uc96a3808&name=c3841931499707584ee26d1ea58dd34.png&originHeight=480&originWidth=599&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=142799&status=done&style=none&taskId=uf5e24c79-d1dd-4ecb-b316-c5e0e3c899c&title=&width=479.2)

