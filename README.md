# LEPT_JSON
学习[RapidJSON](https://github.com/miloyip/rapidjson) 的作者Milo Yip的json-tutorial
* 符合标准的 JSON 解析器和生成器
* 手写的递归下降解析器（recursive descent parser）
* 使用标准 C 语言（C89）
* 跨平台／编译器（如 Windows／Linux／OS X，vc／gcc／clang）
* 仅支持 UTF-8 JSON 文本
* 仅支持以 `double` 存储 JSON number 类型
* 解析器和生成器的代码合共少于 500 行
## 完成所有连续，并用valgrind 测试无内存泄漏
