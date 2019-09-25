# 版本规范

### 1.版本格式
#### 1.1 主版本号.次版本号.修订号  
- 主版本号:整体变化较大或有不向后兼容的改变  
- 次版本号:功能新增或变化   
- 修订号:问题修复或小改动

#### 1.2 日期版本号.希腊字母版本号
- 日期版本号  
格式：yymmdd
- 希腊字母版本号  
	- alpha:内部测试版      
	- beta:外部测试版  
	- RC  
	- release  

#### 1.3 示例
- 0.0.0   
- 0.1.0   
- 1.0.0
- 1.0.0.190903_beta


### 2.控制规范
#### 0.y.z
处于开发初始阶段,不应该被视为稳定版    

#### 1.0.0
用于界定公共API的形成


### 3.版本更迭
#### 3.1 格式  
- 主版本号、次版本号、修订号均从0开始递增
- 0.0.0版本号为初始值，第一个版本号可为0.0.1

#### 3.2 规范
- 主版本更新时，次版本和修订号重置为0
- 次版本更新时，修订号重置为0