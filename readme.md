
1. 配置user信息(溯源)
	git config --global user.name 'your_name'
	git config --global user.email 'your_email'

	config的三个作用域?
		global:对当前用户的所有仓库有效
		local: 只对某个仓库有效
		system:对系统所登录的用户有效

	显示config的配置,加 --list
	git config --list --local
	git config --list --global
	git config --list --system

2. git 仓库的建立
	场景一: 把已经存在的项目代码纳入git管理
		cd 项目代码所在的文件夹
		git init

	场景二: 新建的项目直接用git管理
		cd 到某个文件夹
		git init your_project #会在当前路径下创建和项目名称同名的文件夹
		cd your project
