
# “查看成绩”用例 [返回](../README.md)
## 1. 用例规约

|用例名称|查看成绩|
|-------|:-------------|
|功能|学生查看自己的每个实验的实验成绩及实验评价|
|参与者|学生|
|前置条件|学生需要先登录|
|后置条件| |
|主事件流| |
|备选事件流| |

## 2. 业务流程（顺序图） [源码](../src/ViewScore.puml)
![sequence1](../img/基于GitHub的实验管理平台--查看成绩用例的顺序图.png) 

## 3. 界面设计
- 界面参照:
- API接口调用
    - 接口1：[getOneStudentResults](../inf/getOneStudentResults.md) 

## 4. 算法描述
    无
    
## 5. 参照表
- [STUDENTS](../DatabaseDesign.md/#STUDENTS)
- [GRADES](../DatabaseDesign.md/#GRADES)
- [TESTS](../DatabaseDesign.md/#TESTS)