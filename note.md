# OpenArkCompiler Learning Notes
## 华为开源
- [方舟编译器项目主页] （https://www.openarkcompiler.cn/home）
- [方舟开源代码主站]（https://code.opensource.huaweicloud.com/HarmonyOS/OpenArkCompiler/home)
- [镜像站github] (https://github.com/harmonyos-mirror/OpenArkCompiler)

## 我的开发环境
- 我使用[Vagrant运行Ubuntu16.04虚拟机作为开发环境] (vagrant/README.md)
- git flow: triangle flow
```
$ git remote -v
github	git@github.com:zdndanny/OpenArkCompiler.git (fetch)
github	git@github.com:zdndanny/OpenArkCompiler.git (push)
upstream	https://github.com/HarmonOS/OpenArkCompiler.git (fetch)
upstream	https://github.com/HarmonOS/OpenArkCompiler.git (push)
$ git checkout -b develop upstream/master
```

## 测试记录
- build compiler from src
- run samples 
  
## 相关文档

- 架构设计原理
   - [MAPLE IR Design](doc/MapleIRDesign.md)
   - [RC API](doc/RC_API.md)
   - [Naive RC操作插入原理](doc/Naive_RC_Insertion_Description.md)
   - [虚函数表和接口函数表设计介绍](doc/Vtable_Itable_Description.md)
   - [Phase设计介绍](doc/Compiler_Phase_Description.md)

- [环境配置](doc/Development_Preparation.md)

- [开发者指南](doc/Developer_Guide.md)

- [编程规范](doc/Programming_Specifications.md)



## 许可证
- [LICENSE](license/LICENSE)
- [开源软件声明](license/Third_Party_Open_Source_Software_Notice.md)

