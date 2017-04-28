# 正则表达式

## 类别划分

    - Basic Regular Expression,BRE(基本正则表达式)
    - Extended Regular Expression,ERE(扩展正则表达式)
    - Fast Regular Expression,FRE(固定字符串非正则表达式)

## 特殊字符

| 字符 | BRE/ERE | 含义 |
| :---:| :----:  | :---:|
| \ | both | 通常用以关闭后续字符的特殊意义,`\(...\)`与`\{...\}`则相反地表示开启特殊意义 |
| . | both | 匹配任何单个的字符,但NUL除外 |
| * | both | 匹配在它之前的任何数目(或没有)的单个字符 |
