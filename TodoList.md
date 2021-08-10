

### 重点可参考《流畅的python》 、《Python cookbook》

### Python 对象引用、可变性和垃圾回收

### Python 上下文管理器

### Python 单元测试

### Python 测试、调试和异常

### Python 生成器、迭代器

### Python 回调函数

### 源码阅读

如果一定要推荐一些 python 的源码去读，我的建议是标准库里关于网络的代码。从 SocketServer 开始，补上 socket 模块的知识，熟悉 TCP/UDP 编程，然后了解 Mixin 机制的最佳示例 SocketServer.{ForkingMixIn|ThreadingMixIn}，借这个机会了解 thread/threading 模块，这时会对并发量提出新的要求，就可以读 select 模块，开始对 select/{epoll|kqueue} 有深刻理解，搞懂以后就可以接触一下异步框架 asyncore 和 asynchat。这时开始出现分岔。如果是做 game 等以 TCP/UDP 协议为基础的应用，可以去读 greenlet 和 gevent，



作者：laiyonghao
链接：https://www.zhihu.com/question/20336475/answer/16093609
来源：知乎
著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。