#上传多个文件夹到一个仓库
***
在放项目的文件夹下右键选择git bash here，我的位置是D:\MyFile\Andrio，那么可以在Andrio这个项目右键  
接着输入 <pre><code>git clone https://github.com/windarain/Demo.git</code></pre>

在Android这个项目下就会产生一个与仓库同名的文件夹  

此文件夹下存储有隐藏文件.git,README.md;如果没有README.md这个文件夹的话，就clone一个或自行创建  

然后把要上传的文件放在这个文件夹下，接下去在此文件夹的git里面输入如下的命令
  
1.<pre><code>git init</code></pre>  
2.<pre><code>git add .或者git add 具体的文件夹名</code></pre>  
3.<pre><code>git commit -m "解释"
（我自己输入的是git commit -m "init commit")</code></pre>  
4.<pre><code>git push origin master</code></pre>
