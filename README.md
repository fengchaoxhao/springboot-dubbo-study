# springboot-dubbo-study
springboot-dubbo学习

## 解决Maven版本不同的问题 ##
在项目根目录下执行Maven命令：  
mvn -N io.takari:maven:wrapper -Dmaven=3.1.0  
执行上述命令后在项目根目录下会生成以下目录和文件  
__目录__  
![./mvn/wrapper目录](./images/mvn-wrapper.png)  
__文件__  
![mvnw命令](./images/mvnw.png)  

Linux环境执行命令：  
./mvnw clean install  

Windows环境执行命令  
./mvnw.cmd clean install

## 添加不同Git仓库的项目作为子模块进行聚合开发 ##
在当前根目录下执行如下命令:  
$git submodule add https://github.com/fengchaoxhao/springboot-dubbo-api.git

