Welcome
===========

主题使用Litten制作的[yilia](http://litten.me/2014/08/31/hexo-theme-yilia/)
主题更新: `git clone https://github.com/litten/hexo-theme-yilia.git themes/yilia`

```
git commit -m "first commit"
git remote add origin https://github.com/yudianr/hexo-blog.git
git push -u origin master
```

## 相册的样式文件存放地址：./source/photos/
- 图片处理的python脚本(tool.py  ImageProcess.py)    `./tool.py`
- 裁剪图片(cut_by_ratio):去图片的中间部分，裁剪为正方形
- 压缩图片(compress):把图片进行压缩，方便相册的加载
- 将处理后的图片提交到github上(git_operation)
- 将图片信息处理成json数据格式(handle_photo):采用的方式是读取图片的名字作为其中的text的内容，图片的命名为"最前面是日期，然后用_进行分隔，后面是图片的描述信息，注意不要包含_和.符号"


Reference
===========
- http://litten.me <br><br>
- http://luojh.me/ <br><br>
- http://luojh.me/2018/01/28/blog2/ <br><br>
- http://luckykun.com/ <br><br>
- http://lawlite.me/ <br><br>
- https://github.com/xiaweizi/BackupBlog
- http://xiaweizi.cn/
- https://www.jianshu.com/p/f5c184047e72
- https://mrdear.cn/
