## 说明

1. 安装前需要先指定 JENKINS_HOME 指定 jenkins 数据映射路径

    ```
    export JENKINS_HOME=/srv/jenkins
    ```
   
2. 初次输入密码

    初次访问会让输入密码，密码存储于容器中的 `/var/jenkins_home/secrets/initialAdminPassword` 中，对应宿主机的目录为 `$JENKINS_HOME/secrets/initialAdminPassword`