
[English](./README.md) | 简体中文

# 一个pdf展示组件
>日拱一卒无有尽,功不唐捐终入海

支持流pdf文件预览 和 静态pdf文件预览

本组件最大亮点是支持 ~流~pdf文件预览，而且加上了 类似chrome 默认pdf的功能按钮样式



# ✨ 功能
1. 支持流pdf文件预览
2. ui和chrome默认ui一致

# 📦 安装
`npm install react.pdf.stream --save`


# 🔨 示例
```javascript
import PDFView from 'react.pdf.stream';
ReactDOM.render(<PDFView filePath="required" />, mountNode);
```

# 🤝 欢迎提bug



# 过程记录
* [x] 普通的embed 和 iframe
* [x] 按钮部分，痛苦，因为有ripple效果，搞了半天，待优化
* [x] topbar 和 右侧bar 动画  ，看chrome自带的pdf，emmm，写得真好哦
* [x] 全屏、放大、缩小
* [x] 旋转
* [x] 分页
* [x] loading
* [ ] 监听键盘左右按键，pdf容器部分 监听
* [ ] 双指或鼠标滚轮，放大监听，在pdf展示区域
* [ ] 两种模式切换==》 分页/全部（监听滚动渲染）
* [ ] annotion ==》 记号笔 ，划线，框，添加注释
* [ ] 滚动条样式， 上下滚动条的样式
* [ ] 点击 根据height展示，隐藏topbar，不隐藏 zoombar'
* [ ] 下载，带默认也要给接口
* [ ] 打印，带默认也要给接口
* [ ] 还要给额外的button 地方，可以拿到内部属性






# TODO 
1. 目前pdf文件被转换成canvas，不能编辑和复制，编辑修改pdf，保存；需要判断pdf类型，是否是图片还是文本，针对文本，可以进行编辑 highlight等
2. 兼容性测试
3. 。。。