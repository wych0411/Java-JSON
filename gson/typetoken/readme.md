# TypeToken

> com.google.gson.reflect.TypeToken，从类路径可以推断TypeToken大概的用途。

TypeToken是一个匿名内部类，官方解释是：
> GSON提供了TypeToken这个类来帮助我们捕获像List这样的泛型信息。Java编译器会把捕获到的泛型信息编译到这个匿名内部类里，然后在运行时就可以被getType()方法用反射的API取到。  

实际上就是TypeToken把泛型T转成.class。
