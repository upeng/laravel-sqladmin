assemble sql statements quickly
> 执行sql前做一层sql拼接的封装，再也不用手动拼接sql了！封装底层的复杂增删改查逻辑，调用公共的make方法，返回sql(含占位符？)和绑定参数列表

## sqlcurd特点
* 直接组成PDO可以执行的语句
* 返回值是sql和待绑定参数，避免sql注入
* 减少重复代码的编写
* 规则简单

## 在laravel中使用

* `composer require upstriving/curd`

* config/app的providers中添加一行
`\Upstriving\Curd\SQLAdminProvider::class,`

## 详细说明文档(待更新)
>  公用方法
makeSelect(..)
makeReplace(..)
...



