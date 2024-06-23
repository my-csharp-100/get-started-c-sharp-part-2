# 使用 C# 中的数组和 foreach 语句来存储和循环访问数据序列

|本期版本|上期版本
|:---:|:---:
`Sun Jun 23 20:25:10 CST 2024` | -

```C#
string[] fraudulentOrderIDs = new string[3];

string[] fraudulentOrderIDs = { "A123", "B456", "C789" };
```

* `Length`: 数组的大小

**使用 foreach 遍历数组**

```c#
foreach (string name in names)
{
    Console.WriteLine(name);
}
```