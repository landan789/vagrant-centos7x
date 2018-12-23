## 首次安装步骤

[1]. 步骤一，使用 git clone 下载此仓库代码
```shell
略
```
---------------------------------------

[2]. 步骤二，到 Vagrant 官网，安装最新 Vagrant 版本
```shell
略
```
---------------------------------------

[3]. 步骤三，到 Virtualbox 官网，安装最新 Virtualbox 版本 (也可以使用 hyper-v VmWare, 等 但推薦 Virtualbox)
```shell
略
```
---------------------------------------
[4]. 步骤四，到 PC BIOS 开启 CPU 虚拟化技术
```shell
略
```
---------------------------------------

[5]. 步骤五，到此项目的根目录，使用预先打包好的 shell script 替换配置文件 (如果收悉配置，可以自己手动修改)
```shell
sh vagrant_shells/main.sh
```
---------------------------------------

[6]. 步骤六，置 vars/nodes.yml , 做进阶 配置 (一般可跳过)
```shell
略
```

---------------------------------------
[7]. 步骤七，置 Vagrantfile , 做进阶 配置 (一般可跳过)
```shell
略
```

---------------------------------------

[8]. 步骤八，於 Windows (或 MAC ) 安裝 vagrant 插件
```shell
vagrant plugin install vagrant-vbguest
```

[9]. 步骤九，利用 vagrant 启动虚拟机
```shell
vagrant up
```

[10]. 步骤十，利用 vagrant 於 Windows (或 MAC ) , 強制 執行 
```shell
vagrant up --provision
```