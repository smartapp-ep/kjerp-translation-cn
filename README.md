# kjerp-translation-cn
每个模块对应着一个文件夹，每个文件夹中都包含了这个模块每次修改后的版本文件。以后一有翻译更新必须进行版本控制！！！

步骤：
1.按照正常步骤提交更改后的翻译
  1）git add .
  2）git commit -m “提交说明”
  3）git push origin master
  
2.添加新的标签如v1.0.0.1
  git tag -a v1.0.0.1 -m “版本说明”

3.将新增加的标签push到远程
  git push origin --tags
  
  
  
注：新增加的标签会默认标记最新的提交，所以要先提价再创建新标签