## 第一节 服务器环境 

### 1.1.1 工具GIT

类Unix系统都自带git-core工具，可以通过git克隆别人的代码，用来参考学习。下一节我们会接触到nvm工具，用来管理node版本的工具。我们可以通过命令`git clone https://github.com/creationix/nvm.git`将其下载到本地使用。

如果你的系统是Windows那么你需要一个[git安装包](http://msysgit.github.io/)，下载安装。

### 1.1.2 数据库

#### Mysql

mysql是仅次于Oracle的第二大数据库软件。mysql在各大公司广泛使用。所以如果我们使用nodejs去直接操作数据库的话。那么你遇到最多的可能是mysql数据库，下面我们将来上手mysql的安装体验：

Linux环境下，安装mysql有两种方式：源码安装和二进制包安装。顾名思义，二进制包就是已经编译好的，不需要手动编译就可以直接安装，很方便。建议使用二进制包安装，省事。二进制包安装只需要一行命令足够`yum install mysql-server mysql-devel mysql`。ranghou
