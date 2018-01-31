# page_translation
页面内容选中弹出翻译结果 modal

查询文本语言 请使用 `https://fanyi.baidu.com/langdetect`
参数:
```javaScript
[{"key":"query","value":"你好世界","description":""}]
```


请求翻译结果 使用 `https://fanyi.baidu.com/transapi` api
参数:
```JavaScript
[{"key":"from","value":"zh","description":""},
{"key":"to","value":"en","description":""},
{"key":"query","value":"你好世界","description":""}]
```
(form 参数从第一个 api 中获取)
(`https://fanyi.baidu.com/v2transapi` 需要 token)
