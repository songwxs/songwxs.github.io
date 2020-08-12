## Welcome to my Pages

## Java知识点

#### 1 数据类型知识点

- 数据类型：分为*基本数据类型，引用数据类型*。

**基本数据类型**有8种：四种数字类型（byte，short，int ，long），两种浮点类型（float，double），一种字符类型（char），一种布尔类型（boolean）

**引用数据类型**：数组，类，接口。

*注意long型的默认值为 `0L`，float类型的默认值为 `0.0f`，double类型的默认值为 `0.0d`，boolean默认类型为false。*

- 数据类型的转换：自动类型转换，强制类型转换。

```java
       低  ------------------------------------>  高
     byte,short,char—> int —> long—> float —> double
```

**自动类型转换**(由低转高)直接转换即可。

**强制类型转换**(由高转低，精度损失需要强制转换)，

`eg`：

```java
int i1 = 123;
byte b = (byte)i1;//强制类型转换为byte
```



