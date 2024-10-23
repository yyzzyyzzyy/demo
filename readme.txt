# 自选目录，将这个目录变成git管理的仓库，生成.git文件
git init
# 手动新建文件
# 将文件添加到git仓库中的暂存区
git add 文件名
# 将刚添加的文件提交到仓库中
git commit -m "消息内容/注释"
# git commit后会进入vim界面
"ESC" 后 键盘输入":wq"
# github创建项目（repository）
# 格式:git remote add 别名 git@github.com:GitHub用户名/GitHub仓库名.git
git remote add demo git@github.com:yyzzyyzzyy/demo.git
# git push推送到github仓库(github设置.ssh id_rsa.pub)
git push demo master
