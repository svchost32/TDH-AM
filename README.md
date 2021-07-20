# 7.20

## 内容
管理页只直接呈现所有记录


## 新需求
权限该对应什么功能

>level 0
- 所有内容只读
- 无功能
- 只能看自己的所有记录项

>level 1
- 看到自己的带人
- 评价记录页
- 管理页
  - 从属关系 

>level 1+

### 主要功能设计
- 管理页
  - 管理层级导航栏
    - 默认全部
    - >level 1+
      - 根据数据库查所有带教老师记录
        - 带教老师里再晒选个人
    - >level 2+
  - 功能导航栏
    - >level 1+
    - 非特征排序
      - 登记时间 （默认）
      - 评价时周期
      - 部门
        - >level 2+
      - 工作态度?
    - 特征查询
      - 对象名
      - 带教名
        - >level 1+
      - 工作安排
      - 其他字段？
  
  - 报告主体
    - >level 0 readonly，level 1 改，level 1+ 改查
    - 反馈表内容
      - 单条信息
        - 点击修改
          - >level 0+
  
- 填报
  - 填报提交