# 使用git的方法

* 新建一个项目
  <br>同时需要在本地与服务器各建立一个工程，然后进行匹配
  1. 本地操作
    新建一个本地的目录，用于作为repo的本地目录<br>
    使用git init命令来将该目录标记为项目<br>
    初次配置时使用以下命令<br>
    git remote add origin git@github.com:<I>username</I>/<I>project_name</I>.git<br>
    git push -u origin master<br>
  2. 云端操作
    在github的网页版新建一个repo

* 更新一个项目
    <br>使用git add命令将目录中的文件（更改）添加到git本地仓库中<br>
    使用git commit命令将文件的更改更新到git本地仓库<br>

    先使用git pull命令获取云端项目的更新<br>
    再使用git push命令将本地项目的更新同步到云端<br>