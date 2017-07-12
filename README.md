#关于

This is a fork of [jQuery.hotkeys](https://github.com/tzuryby/jquery.hotkeys)

## 备注:
1、添加对特殊字符的支持，比如点号(.)，以及其他正则表达式特殊字符；
2、添加对范围的支持，比如0-9；

## 用法：
```
    jQuery(document).bind('keydown.0x002E.0-9',function (key, evt){ 
        console.log(key, evt); 
    });

```

