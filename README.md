使用ssh做git clone到本機端會出現異常
# maven-project
Fork from https://github.com/fallskygaoyan/maven-project.git
Source code for Sunny's Jenkins course at Udemy.
克隆仓库的命令:
git clone https://github.com/fallskygaoyan/maven-project.git 

Git 仓库Web页面:
https://github.com/fallskygaoyan/maven-project 

Git仓库的URL (Jenkins里面需要填):
https://github.com/fallskygaoyan/maven-project.git 

Maven 项目类型
在本节课中，当您单击New Item按钮时，您可能看不到Maven项目类型可供选择。

为了有Maven Project类型可选，您需要安装Maven Project Plugin 网址如下：

https://wiki.jenkins-ci.org/display/JENKINS/Maven+Project+Plugin

111
  2222

如果您正在构建一个复杂的maven项目，那么请选择maven项目类型，这是Jenkins专门为基于maven的项目保留的一个项目模板。

Jenkins了解pom . XML文件格式，利用它，可以大大减少手动配置。 

但是考虑到我们的maven项目是一个非常简单的项目，而自由风格项目就足够了，所以这里我们只用了自由风格项目。

查现有SSH密钥:

https://help.github.com/articles/checking-for-existing-ssh-keys/

生成一个新的SSH密钥并将其添加到SSH -agent:

https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/

向你的GitHub帐户添加一个新的SSH密钥:

https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/
 

