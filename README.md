# ansible-containerd-k8s

#### 介绍
基于ansible，使用国内阿里云镜像地址，自动安装 ` containerd.io, kubeadm, kubelet, kubectl ` 

#### 软件架构



#### 使用说明

1. 任意主机安装ansible

2. 下载项目

   ````shell
   git clone https://gitee.com/kuuun/ansible-containerd-k8s.git
   ````

3. 修改`hosts`文件，添加预安装`containerd.io`的主机地址

   ```shell
   [containerd_servers]
   172.16.4.61
   ```

   

4. 执行命令

   ```shell
   ansible-playbook containerd.yaml -k
   ```

   
