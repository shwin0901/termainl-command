#	关于npm

* 查看当前npm包镜像源

  ``` 
  npm config get registry
  ```

* 切换npm镜像源

  ```
  npm config set registry=https://registry.npm.taobao.org/
  ```

* 安装 nrm 全局工具配置 npm 镜像源

  ```
  npm i nrm -g
  
  查看所有可用的镜像源
  nrm ls
  
  切换镜像源
  nrm use taobao
  ```

  

