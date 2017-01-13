
# 一款Mac小软件（用于上传图片到图床生成外链接(支持生成markdown链接)）
> 模仿iPic应用开发，感谢[Mac App 基础开发教程](http://www.macdev.io/)学习指导，感谢[谷歌](https://www.google.com/)的问题解答 
####上传图片到图床，然后直接生成图片链接到剪贴板(支持生成markdown链接)
#### 大大省去了写论坛，博客插图的麻烦事，配合[Chrome插件Markdown here](http://markdown-here.com/)在一切可以写富文本的地方如微信公众号文章，方便快捷得插图



###如果你觉得好，请Star✨下

#### 最新版本下载见最下面

___



#####可能有未知bug，请通过 chenxtdo@gmail.com 给予反馈，阿里阿都
> 本意是打算自己写个，自己用用的。开源，是不打算支持其他图床了（感觉会对iPic造成一定的影响的），因为自己用七牛够了。如果想添加其他图床，自己的动动手（其实就是加个sdk，或者对接下服务的api，这款软件的主要处理我觉得并不在吧）。
___

![Icon_128x128.png](http://7xqmjb.com1.z0.glb.clouddn.com/54979Icon_128x128.png)

####已有功能：
1. 拖拽图片文件到状态栏图标直接上传（随手一拖）
2. 复制图片文件，点击状态栏上传按钮上传（CMD＋C 图片后 点击应用上传件直接上传）
3. 用截图工具保存在剪贴板的图片，点击上传直接上传(**此处可能有BUG，现阶段通过七牛云的SDK进行上传，好像有点BUG，无法指定data的格式，也有可能操作有误。现阶段通过七牛云转码接口进行处理**)
4. 配置自己的图床（暂时支持七牛云）
5. 增加上传进度展示
6. 新增上传图片的展示，与最近5张的上传历史，点击直接复制链接
7. 增加自动自动上传功能
8. 自由切换普通链接，markdown链接

![146899582127018.jpg](http://7xqmjb.com1.z0.glb.clouddn.com/146899582127018.jpg?imageView2/0/format/jpg)



####ToDo:

1. ~~上传的历史列表（可以复制之前的链接）~~
2. ~~上传进度展示（网速慢的时候我都不知道有没有在传呀。－ －！）~~
3. 多图同时上传(一次性好几张图一起来更佳爽)
5. 图片的比例更改（目前可以通过更改七牛云的链接进行裁剪，[七牛云图片处理文档](http://developer.qiniu.com/code/v6/api/kodo-api/image/imageview2.html)） 
6. 去掉SDK，通过API上传图片
4. 等等




#### 下载演示

**现在应该能满足基本需求，功能不断完善中**

[演示下载](http://lzqup.com)

# License
MIT

