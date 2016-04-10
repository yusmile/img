# repository
博客图片

打开它，看到网址，将网址中github.com改为raw.githubusercontent.com,这就是你的图片外链地址了。

https://github.com/yusmile/img/blob/master/cometrue/%E6%97%A0%E6%A0%87%E9%A2%982.ICO
https://raw.githubusercontent.com/yusmile/img/master/cometrue/%E6%97%A0%E6%A0%87%E9%A2%982.ICO


至此大功告成，你的图片已经在GitHub服务器上了。
缺点是只有原图，没有其他的尺寸。 以后传之前先调整一下大小吧
然后上传好了后，你在你的repository上找到你的图片，如下图这样：

打开它，看到网址，将网址中blob改为raw,这就是你的图片外链地址了。


别忘了将网址中blob改为raw

大功告成！！

PS. 如果你像我一样比较懒觉得输入三行命令比较烦的话可以定义一个别名alias，我的下一篇博客里会讲到怎么做，下面是我的例子：

alias tp='tp(){ cd E:/SkyDrive/img;git add .;git commit -m "blog_img";git push origin master;};tp' 