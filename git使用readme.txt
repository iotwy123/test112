第一步：安装git。默认选项安装
第二步：在工程文件中，右键git bash here 打开终端
第三步：输入命令git init  生成隐藏文件.git                //初始化git仓库         该仓库会对我们项目代码备份的文件
第四步：在git中设置下当前使用的用户是谁（每一次备份都会把当前备份者的信息存储起来）	 
	git config --global user.name "wy"   双引号为自己名称	 
	git config --global user.email  "1124233930@qq.com"
第五步：把代码存储到.git仓库中
	打开仓库门(.git隐藏文件)           git add ./test.txt			//相当于把文件放到大门口
	把代码放到仓库的房间里	git commit -m "我们完成了第一个功能"  //m指的是新增一个消息
第六步：查看当前状态    git status
第七步：git add ./          //将所有工程文件下的文件都提交到大门口，     git commit -m "说明信息"
第八步：git commit --all -m "说明"    git add 和 commit 的结合版
第九步：git log     //查看日志
第十步：git log --oneline //查看简洁版日志
第十一步：git reset --hard Head~0  //将修改的文件恢复为最近的一个版本


	