# lodashtranslationV4.17.4
> # util
>> ## attempt(func,[args])
>>> + Arguments:  
>>> func(function):需要尝试的函数  
>>> \[args\](...\*):提供给函数使用的参数  
>>> + Returns:  
>>> (\*)返回尝试函数的结果或者错误对象  
>>> + Notes:  
>>> **使用这个方法执行可能会报错的函数的话，不会由于报错影响后续代码执行，如果函数发生报错会以一个错误对象形式返回，不会阻塞程序运行。**  
>>> ![](https://raw.githubusercontent.com/thezj/lodashtranslationV4.17.4/master/utilattempt1.png)  

>> ## bindAll(object,[methodName])
>>> + Arguments:  
>>> object:需要绑定注册方法的对象  
>>> \[methodName\](...string):绑定的方法名称  
>>> + Returns:  
>>> (object)返回绑定的对象
>>> + Notes:  
>>> **对象的方法以后再遇到绑定到其他地方的时候object.func1.call(otherObject),不会改变方法内部的上下文对象this，还是指向原始对象object**  
>>> ![](https://raw.githubusercontent.com/thezj/lodashtranslationV4.17.4/master/bindall1.png)
