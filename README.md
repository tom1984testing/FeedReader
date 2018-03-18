# 项目预览
通过该项目熟悉jasmine测试框架的使用，学习采用jasmine编写单元测试。

# 主要知识点
1.判断字符串s非空：
expect(s).not.toBeNull();
expect(s.length).not.toBe(0);

2.判断布尔型变量
expect(b).toBe(true);
expect(b).toBe(false);

3.异步方法
expect异步方法的返回结果，需要使用beforeEach方法, 并且beforeEach方法参数是带有done参数的函数， done是
一个完成函数，done函数被执行表示异步函数执行完成，接下来继续之后后面的it

# 何处下载项目
git clone https://github.com/tom1984testing/FeedReader
下载后运行index.html， 页面下面展示jasmine测试套件的执行结果

