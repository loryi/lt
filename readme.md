#Project LT
LT 是 language transforms 的缩写，旨在通过程序实现实时的翻译外语的功能


## 语言翻译
### 1.暂时会借用百度的翻译API进行对应的翻译操作
### 2.百度免费使用的API存在有1秒调用一次的限制

## 项目分级
### 1.同外部翻译API对接的接口层 language
### 2.提供给内部调用的翻译层 transform
### 3.各种来源的翻译实现层 service
### 4.可能会存在的客户端功能 client