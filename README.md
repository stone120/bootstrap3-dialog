bootstrap-dialog
================
Use Guidance & install steps: you can get from:
[original nakupanda bootstrap3-dialog](https://github.com/akinoniku)

See live examples here: <a href="http://nakupanda.github.io/bootstrap3-dialog/">http://nakupanda.github.io/bootstrap3-dialog/</a>

================

## 修订原因 

项目组使用Dialog控件用做信息采集，主要采用load信息录入页面方式。
> 根据信息录入页面的大小需要定制Dialog的显示大小
> 信息录入页面如果包含多标签，Dialog的自适应不生效（仅显示一部分页面）

## 用于信息采集的典型Dialog
|大小|css样式|信息展示样式|CSS样式|
|----|------|-----------|-------|
|最大|dlg-max|自动高度|dlg-max-auto|
|最大|dlg-max|固定高度|dlg-max-fixed|
|大|dlg-lg|自动高度|dlg-lg-auto|
|大|dlg-lg|固定高度|dlg-lg-auto|
|普通|dlg-normal|自动高度|dlg-normal-auto|
|普通|dlg-normal|固定高度|dlg-normal-auto|

## 使用说明
1. 送入参数dlgStyle,用来定义dialog的css样式
2. 送入参数messageStyle,用来定义dialog内的message <div> 的css样式


CSS层及结构和 本次添加的css样式示意图如下：

![dom 层级及其css样式](http://om49hkcv7.bkt.clouddn.com//image/bootstrap-dialogimage2017-3-31%2015-23-55.png)

## 示例 待补充
================

Licensed under The MIT License.
