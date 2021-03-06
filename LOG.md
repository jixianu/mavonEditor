# 更新日志

- **2.0.6** 添加选项是否高亮代码，详见 props: ishljs(17.6.25 / [CHENXCHEN](https://github.com/CHENXCHEN))
- **2.0.2** 调整编辑模式，详见 props: subfield、default_open(17.6.24)
    - 新增props: placeholder 输入框为空时默认提示文本
    - 整理代码状态机
- **2.0.0** highlight.js语言高亮文件异步调用渲染(17.6.20 / [CHENXCHEN](https://github.com/CHENXCHEN))
- **1.7.3** 更改事件监听方式，修正粗体样式(17.6.15 / [CHENXCHEN](https://github.com/CHENXCHEN))
- **1.7.0** 取消单栏编辑模式实时渲染(17.6.14 / [CHENXCHEN](https://github.com/CHENXCHEN))
    - 添加图片预览(粘贴板图片复制粘贴本地预览、图片拖拽本地预览、手动选择图片本地预览)
    - 添加图片文件添加删除事件
    - 删除to-markdown部分
- **1.6.3** 新增Markdown样式选择 props：code_style(17.6.9 / [yyyybzzzz PR](https://github.com/yyyybzzzz))
- **1.6.1** 新增props：enabled编辑开关、toolbarsFlag工具栏是否显示(17.5.26)
    - 修复subfield = true初始化时候不显示内容
- **1.5.6** 支持语言切换 ， 新增英文文档(17.5.11)
- **1.5.3** 拓展markdown渲染规则——KaTeX$公式 ， 修改help文档(17.5.6 / [CHENXCHEN](https://github.com/CHENXCHEN))
- **1.5.2** 优化项目结构(17.5.6 / [CHENXCHEN](https://github.com/CHENXCHEN))
    - 将toolbar抽离为两个单独vue文件，事件提取为toolbar_left.js和toolbar_right.js
    - 抽离stylus样式为mavon-editor.styl
    - 调整md.css位置至lib/css
- **1.5.1** 添加postcss插件，压缩插件体积，分离markdown样式(样式需单独引入，参考上述用法)(17.5.6 / [CHENXCHEN](https://github.com/CHENXCHEN))
- **1.4.8** 优化项目结构,添加webpack-dev-server的开发测试(17.5.4 / [CHENXCHEN](https://github.com/CHENXCHEN)）
- **1.4.7** 图标局部引入,减少文件体积(17.4.26）
- **1.4.2** 支持开启标题导航 ,快捷键监听对象更改为document（17.4.25）
- **1.4.0** 重构代码（17.4.24）
- **1.3.5** 增加撤销键、清空键、保存按钮 , 修复底部展示不完整BUG
- **1.3.4** 多个编辑器快捷键/组合键监听覆盖 , props.toolbars 传递规则纠正(传入值整体覆盖默认值)
- **1.3.3** 多个编辑器z-index冲突
- **1.3.2** props 传递方法 更改为 v-on 绑定方法
