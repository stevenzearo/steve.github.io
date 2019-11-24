# SCALA NOTES
## String
### String format
#### s插值器
```scala
val steve: String = "steve"
val score: Float = 86.458f
val s: String = s"name:${steve}, score:${score}"
```
s插值器<font color="red">仅支持值替换, 不支持字符串格式化</font>（%d,%f,%s等）在字符串中无  
效，若要进行字符串格式化可配合"".format(args...)使用
#### f字符串格式化
```scala
val steve: String = "steve"
val score: Float = 86.458f
val s: String = s"name:${steve}, score:${score}%.2f"
```
s插值器<font color="red">既支持值替换，又支持字符串格式化</font>（%d,%f,%s等）  


[go index](README.md)