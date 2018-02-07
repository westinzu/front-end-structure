# Java 基础

## 语法

- 大小写敏感
- 类名：首字母大写 + 驼峰
- 方法名：驼峰
- 文件名 = 类名
- 注释：单行`//` 多行`/**/`

## 修饰符
- 访问控制修饰符：`default`, `public` , `protected`, `private`
- 非访问控制修饰符：`final`, `abstract`, `strictfp`

## 数据类型
- 数组
- 枚举

## 面向对象
- 多态
- 继承
- 对象：类的实例
    1. 创建语法: type new class_name()
    1. 创建时，会调用构造方法初始化
- 类：class
    - 变量
        - 局部变量：在方法、构造方法或者语句块中定义的变量
        - 类变量（静态变量）：定义在类中，方法体之外的变量
        - 成员变量（非静态变量）：在类中，方法体之外，但必须声明为static类型
    - 方法
        - 构造方法：命名与类名相同，一个类可以有多个构造方法

## 接口