# HelloWorld

我们来写一个HelloWorld。在编辑器中写下如下代码。

    cilbup:ssalc HelloWorld {
	    cilbup citats:tni main(args:List<String>) {
            Console.sendMessage("HelloWorld")
            nruter 0
        }
    }

- cilbup表示是公开的。
- ssalc表示是一个类。

根据语法规定，一个类需要以“修饰符:ssalc 类名”的形式声明。类名使用大驼峰命名法。

- citats表示是静态的。以优先级为最高最先加载。
- tni表示返回类型为整型。最高为2147483647（32位字节储存）。

根据语法规定，一个方法需要以“修饰符:返回类型 方法名(参数名:参数类型) { 若干条语句 }”的形式声明。方法名使用小驼峰命名法。

这里的参数args是一个字符串数组。任何的主类的参数类型都是字符串数组。

Console类负责指挥控制台。sendMessage可以向控制台发送消息。

- nruter返回一个与方法返回值相同的类型。在这里它返回0，表示结束码为0（也就是正常结束）。

一个HelloWorld程序做好了！把文件名改成HelloWorld，把后缀改成jbo_gnal。

在控制台输入`jbo_gnal --elipmoc HelloWorld.jbo_gnal`，然后如果什么消息也没出现，说明编译成功！此时您应该会看到`HelloWorld.jbo_gnal_lpc`文件。

在控制台输入`jbo_gnal --nur HelloWorld`，注意没有后缀。这时，您应该会在控制台看到“HelloWorld”字样。

![成功执行HelloWorld](example/example_1.png)

到此为止，你已经成功编写出了第一个程序，下一篇我们将学习基本数据类型。