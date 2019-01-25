## 安装
```
npm i -save dragupload
或
yarn add dragupload
```
## 使用
```
<dragupload @getFile="upload" accept=".csv, application/vnd.openxmlformats-officedocument.spreadsheetml.sheet, application/vnd.ms-excel"></dragupload>
```
## 参数

参数 | 含义| 类型| 是否必须
accept|	允许上传的文件类型|	String|	true
## 事件

参数 | 含义 | 类型
getFile|	文件选择事件|	event